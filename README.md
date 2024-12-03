# ProtonAOSP builds for Google Pixel 5 (redfin)

Just a regular ProtonAOSP 11.6.0 & 12.4.1 builds but packed as OTA package. 
For some reason, kdrag0n didn't ever released ProtonAOSP builds as OTA packages for modern Pixel devices, therefore today we cannot use this great ROM with, for example, [avbroot,](https://github.com/chenxiaolong/avbroot) which allows to run a custom ROM with root-access paired by AVB and locked bootloader.

So [I built the ROM](https://protonaosp.org/developers/build) in its original form using the latest sources for both Android 11/12.1 versions, but now in OTA package format (factory images available too). You can freely use it together with avbroot. **Builds are signed** with private keys, just like kdrag0n's official builds.

Notes:
1. The factory images archive does not contain `avb_custom_key` for bootloader, implying that you will assign it with your own keys.
2. ROM is bundled with the same stock firmware as official ProtonAOSP versions (`RQ3A.210805.001.A1` for Android 11 and `SQ3A.220705.003.A1` for Android 12.1), so you don't have to flash required firmware version beforehand.

Build are only compatible with Google Pixel 5 (redfin) and comes with pre-installed GApps. No further support or updates are implied.

[Visit website](https://protonaosp.org) • [Download](https://github.com/reddxae/protonaosp-redfin-ota/releases) • [Source code](https://github.com/ProtonAOSP/android_manifest)
