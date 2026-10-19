# Public developer website

GitHub Pages root for <https://pamontag-org-ghe.github.io/>.
The game community website and all player feedback live at:
<https://github.com/pamontag-org-ghe/bastionbrawl-public>.

This repository contains only a landing page and public advertising authorization.
It contains no game source code, assets, credentials or deployment configuration.
GitHub Pages publishes the root of `main`; no custom domain is required.

## Advertising authorization

Canonical URL: <https://pamontag-org-ghe.github.io/app-ads.txt>.
Keep `app-ads.txt` identical to the copy in `bastionbrawl-public`.
It authorizes the Google AdMob publisher supplied by the developer.

Use <https://pamontag-org-ghe.github.io/bastionbrawl-public/> as the developer
website in Google Play. AdMob discovers `app-ads.txt` at the hostname root,
not in the project subdirectory. Verification still depends on the public
store listing, store association and Google's crawler; publishing this file
does not activate advertising.

This root is shared by all project Pages sites under this organization.
Coordinate changes to seller authorization across its apps.
