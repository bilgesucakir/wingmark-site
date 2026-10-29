# Wingmark site

<p>
  <a href="https://apps.apple.com/us/app/wingmark-birdwatching-diary/id6820532421"><img src="assets/app-store-badge.png" width="160" alt="Download on the App Store"></a>
</p>

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fwingmarkapp.com&label=wingmarkapp.com&up_message=online&down_message=down)](https://wingmarkapp.com)

Public website for the [Wingmark iOS app](https://github.com/bilgesucakir/wingmark-ios), hosted on Cloudflare at https://wingmarkapp.com/

Every page exists in English and Turkish. A toggle in the header switches between the two versions of the same page.

| English | Turkish | Used for |
|---|---|---|
| `/` (`index.html`) | `/index-tr` | Landing page, App Store marketing URL |
| `/privacy` | `/privacy-tr` | Privacy Policy (App Store Connect + in-app link) |
| `/support` | `/support-tr` | App Store support URL |
| `/accessibility` | `/accessibility-tr` | What the app supports for accessibility, and what it does not |
| `404.html` | (same page, both languages) | Not-found page |

Each address is a file of the same name with `.html` in the repository (for example `/privacy` is `privacy.html`).

Plain HTML with one stylesheet (`style.css`) and a self-hosted font (Literata, SIL OFL, in `fonts/`).
No build step, no trackers, no third-party requests.
