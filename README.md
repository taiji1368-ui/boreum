# 보름달력 (Boreum) — Support & Privacy

Public support and privacy pages for the iOS app **보름달력 / Boreum: Korean Lunar Calendar**, in Korean and English.

Live: <https://taiji1368-ui.github.io/boreum/>

| Page | URL | Used for |
| --- | --- | --- |
| Landing | `/` | Entry point · App Store Connect "Marketing URL" |
| Support & FAQ (ko + en) | `/support.html` | App Store Connect "Support URL" |
| 개인정보처리방침 (ko) | `/privacy.html` | App Store Connect "Privacy Policy URL" (Korean) · in-app link |
| Privacy Policy (en) | `/privacy-en.html` | App Store Connect "Privacy Policy URL" (English) · in-app link |

`app-ads.txt` for this app is served from the domain root repository
[`taiji1368-ui.github.io`](https://github.com/taiji1368-ui/taiji1368-ui.github.io) — it covers every app of the same AdMob publisher.

## These files are generated — do not edit them by hand

The single source of truth is the app repository (`OhengCalendar`, folder `docs/store/`):
`privacy-policy/index.html`, `privacy-policy/en.html`, `support/index.html` and `site/`.
A hand-edited copy here would drift from what the app and the store listing say.

To change a page, edit it in the app repository and regenerate:

```
tools/dev/build-site.sh <path to a checkout of this repository>
```

## App

* iOS bundle `com.boreum.calendar` · App Store Connect Apple ID 6838666693
* Seller DDONTTI STUDIO · <ddontti_studio@outlook.kr>

No trackers, no analytics, no third-party fonts or scripts are loaded by these pages.
