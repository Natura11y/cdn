# Natura11y browser assets

Compiled CSS, JavaScript, and icon fonts for websites using Natura11y, maintained by Avidano Digital.

The current release manifests provide the exact jsDelivr URLs and SHA-384 integrity values:

- [Core CSS and JavaScript](core/manifest.json)
- [Icon stylesheets and fonts](icons/manifest.json)

Use stylesheet links for CSS and a deferred script for Core JavaScript. Load application theme styles after Core and initialize Core only once. When adding an integrity value, also set `crossorigin="anonymous"`. The icon stylesheet loads its matching fonts from the same release.

Core and Icons have independent versions; upgrade each deliberately. Existing release tags are never replaced. Use their fixed URLs from the manifests, not the moving `main` branch, in production.

New browser releases are built and published by the private Natura11y release workflow. This repository contains only browser distribution files and their notices.

Natura11y is maintained as proprietary software by Avidano Digital. The license and any third-party notices shipped with each tagged release govern those files. Public delivery does not grant additional rights.
