# RIPPLE Game SDKs

Pinned third-party SDK tarballs for [RIPPLE Game Base](https://github.com/namdev26/ripple-game-base).

The files are attached to GitHub Releases, one release per SDK set. The TOOL Hub SDK page in RIPPLE Game Base downloads the exact file listed in its `Editor/Sdk/SdkCatalog.json`, checks its SHA-256 and writes a `file:RippleSdks/...` entry into the game's `Packages/manifest.json`. Do not install these SDKs by hand.

## Set `sdks-0.4.0` (RIPPLE Game Base 0.4.0)

| SDK | Package | Version | Source |
| --- | --- | --- | --- |
| External Dependency Manager | com.google.external-dependency-manager | 1.2.186 | Google Unity archive |
| Firebase App | com.google.firebase.app | 13.1.0 | Google Unity archive |
| Firebase Analytics | com.google.firebase.analytics | 13.1.0 | Google Unity archive |
| Firebase Remote Config | com.google.firebase.remote-config | 13.1.0 | Google Unity archive |
| Firebase Crashlytics | com.google.firebase.crashlytics | 13.1.0 | Google Unity archive |
| Firebase Messaging | com.google.firebase.messaging | 13.1.0 | Google Unity archive |
| Google Mobile Ads | com.google.ads.mobile | 11.0.0 | OpenUPM |
| AppsFlyer | appsflyer-unity-plugin | 6.17.900 | Repacked from the official v6.17.900 tag |
| AppLovin MAX | com.applovin.mediation.ads | 8.5.1 | **Not in this repository.** Its license does not allow redistribution; RIPPLE Game Base downloads it from AppLovin's own registry. |

`sdks.json` lists every file with its size, SHA-256, original source and license. Each SDK keeps its original license, copied in `LICENSES/`. This repository adds no code of its own.
