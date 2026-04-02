### zInstaller
zInstaller is an Objective-C Library for installing signed iOS IPA files easily.

## What does this use for installing signed IPA files?

This library gets the necessary information about the IPA file and contacts a Cloudflare worker to host the .plist file for the IPA, then generates an itsms-services:// URL for installing the IPA.
