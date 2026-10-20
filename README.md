# sunrep-support

Static support, privacy and terms site for the Sunrep app (EN + TR).
Planned URL: https://iunalk.github.io/sunrep-support/ (GitHub Pages, `main` branch, root).

Hand-written HTML/CSS. No frameworks, scripts, trackers, cookies or external fonts.

```
index.html              EN home          tr/index.html
privacy/index.html      EN privacy       tr/privacy/index.html
terms/index.html        EN terms         tr/terms/index.html
support/index.html      EN support/FAQ   tr/support/index.html
assets/site.css         shared styles (Sunrep palette, light/dark, reduced motion)
assets/fonts/           Nunito (SIL OFL, see OFL.txt), self-hosted
assets/icon.png         app icon (from 01-sunrep/assets/marka/ikon_1024.png)
```

The app links to `/privacy/` and `/terms/` (`01-sunrep/lib/sabitler.dart`); keep those paths stable.

TODO before launch: real App Store / Google Play URLs (`href="#"` on both home pages) and real screenshots.

Local preview: `python3 -m http.server 8000`, then open http://localhost:8000/.
