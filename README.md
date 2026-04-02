### zInstaller
zInstaller is an Objective-C Library for installing signed iOS IPA files easily.

## How does this library work?

This library gets the necessary information about the IPA file uploaded through Objective C source code and contacts a Cloudflare worker to host the .plist file for the IPA, then generates an itsms-services:// URL for installing the IPA.
