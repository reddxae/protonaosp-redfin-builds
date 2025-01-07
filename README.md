# ProtonAOSP builds for Google Pixel 5 (redfin)

Just regular ProtonAOSP 11.6.0 & 12.4.1 builds, provided as OTA packages.  

For some reason, [kdrag0n](https://github.com/kdrag0n) didn't ever released ProtonAOSP builds as OTA packages for relatively modern Pixel devices, therefore today we can't use this great ROM with [avbroot,](https://github.com/chenxiaolong/avbroot) powerful tool which allows to run a custom ROM with root-access paired by AVB and locked bootloader.

So [I built the ROM](https://protonaosp.org/developers/build) in its original form using the latest sources for both Android 11/12.1 versions, but now in OTA package format (factory images available too). You can freely use it together with avbroot. **Builds are signed** with private keys, just like kdrag0n's official builds.

Notes:
1. The factory images archive does not contain `avb_custom_key` for bootloader, implying that you will assign it with your own keys.
2. Factory images coming with prebuilt stock firmware (`RQ3A.210805.001.A1` for Android 11 and `SQ3A.220705.003.A1` for Android 12.1), so you don't have to flash it beforehand. If you're installing the OTA build, it might be required to flash the factory images first, as OTA doesn't contain firmware.
3. For ProtonAOSP 11.6.0, I've made a separate build with [Proton Kernel 2.1](https://github.com/kdrag0n/proton_kernel_redbull/releases/tag/v2.1) prepackaged, that way you can use it with locked bootloader. It retains all the same benefits. Actually I made it just to have all Proton stuff done, I don't recommend using this kernel today. It seems to be not very compatible with modern heavy applications and on the contrary jittering down the device.

Additionally, I offer personal builds of ProtonAOSP 11.6.0. Changes:
* **Fixed support for modern versions of Magisk/KernelSU.** [Find out how if you need so.](https://gist.github.com/reddxae/749b30675099e6bec4195fbe71ea0bb4)
* Media volume steps raised to 35.
* Updated fonts: FiraCode [6.2,](https://github.com/tonsky/FiraCode/releases/tag/6.2) Source Serif [4.005.](https://github.com/adobe-fonts/source-serif/releases/tag/4.005R)
* System emoji font replaced with [Apple's implementation](https://emojipedia.org/apple) (currently used version is 17.4).

You can find my personal builds under [11.6.0 release tag.](https://github.com/reddxae/protonaosp-redfin-builds/releases/tag/11.6.0) They are provided as OTA only.

___
Builds are only compatible with Google Pixel 5 (redfin) and come with pre-installed GApps. No further support or updates are implied.

[Visit website](https://protonaosp.org) • [Download](https://github.com/reddxae/protonaosp-redfin-ota/releases) • [Source code](https://github.com/ProtonAOSP/android_manifest)
