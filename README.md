# Bottle Hop — public privacy policy

Privacy policy: https://florincor.github.io/bottlehop-privacy/

Data-deletion instructions: https://florincor.github.io/bottlehop-privacy/data-deletion.html

Developer: Florin Cordunianu — cordunianuflorin@gmail.com

This repository contains only public policy pages and their styles. The game source
and packaged builds are maintained separately.

## Current scope

The policy describes the inspected Bottle Hop Android development build: device-local
scores and settings, optional on-device motion controls, and no account or cloud save.
Advertising is planned. The developer confirmed Google AdMob as the advertising
provider on 14 October 2026.
The development build has no Mobile Ads, UMP, separate analytics, or cloud
crash-reporting SDK. The public policy explicitly labels its advertising disclosures
and consent controls as planned.

Before the first ad-supported release, confirm the advertising provider, actual SDK
and mediation configuration, consent and privacy-options behavior, target audience,
and data retention practices. Update the policy to reflect the released app and its
store Data safety disclosures; add the policy URL inside the app and in the store
listing. Publishing this policy does not integrate ads or consent into the game.

## Publishing

- Edit `index.html`, `data-deletion.html`, and `styles.css`.
- Update the policy revision date when practices change.
- Keep `.nojekyll`.
- Commit to the repository's default branch. GitHub Pages serves the root directory.
- Local preview: `python3 -m http.server 8768 --bind 127.0.0.1`.

## Sources checked on 14 October 2026

- [Google Mobile Ads data disclosure](https://developers.google.com/admob/android/privacy/play-data-disclosure)
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google advertising controls](https://policies.google.com/technologies/ads)
- [Google UMP integration guide](https://developers.google.com/admob/android/privacy)
- [Google Play User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311?hl=en)
- [European Commission privacy rights information](https://commission.europa.eu/law/law-topic/data-protection/information-individuals_en)
- [GitHub Pages data collection](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection)
