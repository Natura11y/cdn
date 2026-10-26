# Natura11y browser assets

Compiled CSS, JavaScript, and icon fonts for websites using Natura11y, maintained by Avidano Digital.

Use a fixed release tag with jsDelivr:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Natura11y/cdn@core-5.2.6/core/natura11y.css" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Natura11y/cdn@icons-2.3.0/icons/natura11y-icons.min.css" />
<script defer src="https://cdn.jsdelivr.net/gh/Natura11y/cdn@core-5.2.6/core/natura11y.js"></script>
```

Load application theme styles after Core. The icon stylesheet loads its matching fonts from this same release. Core and Icons have independent versions; upgrade each deliberately. Existing release tags are never replaced. Do not use the moving `main` branch in production URLs.

Each release includes a `manifest.json` with its exact URLs and SHA-384 integrity values. New browser releases are built and published by the private Natura11y release workflow. This repository contains only browser distribution files and their notices.

Natura11y is maintained as proprietary software by Avidano Digital. The license and any third-party notices shipped with each tagged release govern those files. Public delivery does not grant additional rights.
