# Android-CAs-Filtered-ISP
Magisk module that Adds internet filtered ISPs (Such as NetFree, NetSpark, Rimon, Hadran etc.) CA certificates as system
Certificates.

## prerequisites:
* Rooted android with Magisk 20.0 and above.

## installation:
* Download the zip file from [Here](https://github.com/Sivan22/ca-netfree/releases).
* Open Magisk on your device.
* Under the section **modules**, select **from storage**, and choose the zip file.
* Reboot.

### solution for chrome above 100.0
the latest versions of Google chrome will not work with system certificates. 

the solution is to hide the root from chrome and to install a user certificate.

* is magisk app -> settings turn on zygisk and in the hiding list check chrome.
* download the certificate (e.g. from [here](https://netfree.link/wiki/%D7%94%D7%AA%D7%A7%D7%A0%D7%AA_%D7%AA%D7%A2%D7%95%D7%93%D7%94_%D7%91%D7%90%D7%A0%D7%93%D7%A8%D7%95%D7%90%D7%99%D7%93)) and install it as user certificate.
