# protonaosp-redfin-builds
Just a regular ProtonAOSP 12.4.1 build but packed as OTA package. 
For some reason, kdrag0n didn't ever released ProtonAOSP builds as OTA packages for modern Pixel devices, therefore today we cannot use this great ROM with, for example, [avbroot,](https://github.com/chenxiaolong/avbroot) which allows to run a custom ROM with root-access paired by AVB and locked bootloader.

So [I built the ROM](https://protonaosp.org/developers/build) in its original form using the latest sources but now in OTA package format (factory images available too). You can freely use it together with avbroot. **ROM is signed** with private keys, just like kdrag0n's official builds.

1. The factory images archive does not contain avb_custom_key for bootloader, implying that you will assign it with your own key.
2. ROM is bundled with the same stock firmware as official ProtonAOSP 12.4.1 (SQ3A.220705.003.A1).

Build are only compatible with Google Pixel 5 (redfin) and comes only with pre-installed GApps. No further support or updates are implied.

[Download](https://github.com/reddxae/protonaosp-redfin-builds/releases) • [Source code](https://github.com/ProtonAOSP/android_manifest/tree/sc-qpr3)
