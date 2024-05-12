# One UI Home 33 Magisk Module

## DISCLAIMER
- One UI apps and blobs are owned by Samsung™.
- The MIT license specified here is for the Magisk Module only, not for One UI apps and blobs.

## Descriptions
- Home launcher app by Samsung Electronics Co., Ltd. ported and integrated as a Magisk Module for all supported and rooted devices with Magisk

## Sources
- https://apkmirror.com com.sec.android.app.launcher (target SDK 33), com.samsung.android.rubin.app, com.samsung.android.app.galaxyfinder, & com.sec.android.provider.badge by Samsung Electronics Co., Ltd.
- BadgeSettings.apk by frknkrc44

## Screenshots
- https://t.me/androidryukimods/1503

## Requirements
- NOT in One UI nor Touchwiz ROM
- Android 13 and up
- Magisk or KernelSU installed
- One UI Core Magisk Module or above installed https://github.com/reiryuki/One-UI-Core-Magisk-Module
- Add media page to Home screen option requires Google app installed https://play.google.com/store/apps/details?id=com.google.android.googlequicksearchbox or ported Samsung News/Free/Daily/Bixby Home app (com.samsung.android.app.spage) if it's exist.
- Gesture navigation requires android.permission.INJECT_EVENTS. The permission can only be granted in AOSP signatured ROM or disabled Android Signature Verification in Android 13 and bellow.

## Installation Guide & Download Link
- Install One UI Core Magisk Module first: https://github.com/reiryuki/One-UI-Core-Magisk-Module
- If you want to activate the recents provider, READ Optionals bellow!
- Install this module https://www.pling.com/p/2103361/ via Magisk app or KernelSU app or Recovery if Magisk installed
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot afterwards
- Change your default home to this launcher via Settings app (or you can copy the content of default.sh and paste it to Terminal/Termux app. Type su and grant root first!)
- Go to app info of Finder app and allow the network access
- If you want to use Add media page to Home screen option, you need to install Google app https://play.google.com/store/apps/details?id=com.google.android.googlequicksearchbox or ported Samsung News/Free/Daily/Bixby Home app (com.samsung.android.app.spage) if it's exist.
- If you want to change some configurations, read Troubleshootings bellow!

## Tested on
- Android 13 CrDroid ROM
- Android 14 LineageOS ROM

## Optionals & Troubleshootings
- https://t.me/androidryukimodsdiscussions/46153
- Global: https://t.me/androidryukimodsdiscussions/60861
- Global: https://t.me/androidryukimodsdiscussions/29836

## Support & Bug Report
- https://t.me/androidryukimodsdiscussions/2618
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
- https://t.me/androidryukimodsdiscussions/2619


