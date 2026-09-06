# onyx-legal

The privacy policy, terms of use and support pages for **Onyx Scan**, served by
GitHub Pages and linked from the App Store and Play Store listings and from
inside the app (Settings and the paywall).

- Privacy Policy — <https://hamzacakmakk.github.io/onyx-legal/privacy.html>
- Terms of Use — <https://hamzacakmakk.github.io/onyx-legal/terms.html>
- Support — <https://hamzacakmakk.github.io/onyx-legal/support.html>

Plain static HTML, no build step: edit a file, push to `main`, and Pages
republishes within a minute. The source of truth for these pages is this repo —
`onyx-scan/site/` in the app repo is where they were first written.

The in-app links live in `app.json` under `expo.extra` and are read through
`src/lib/links.ts`, so changing a URL there is a config change and a rebuild.
