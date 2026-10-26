# Third-party artwork and notices

Brand icons identify the services they represent. Their names and artwork belong to their respective owners and remain subject to those owners’ brand guidelines. Use them for relevant service links, preserve their geometry and proportions, and follow the linked guidance for color, clear space, labeling, and permitted uses. Do not imply endorsement.

The following source assets were checked on 25 October 2026:

| Icon | Official source | Source variant |
| --- | --- | --- |
| Threads | [Meta Brand Resource Center](https://www.meta.com/en-gb/brand/resources/threads/) | Black icon, `threads-logo-black.svg` from the official logo pack |
| Pinterest | [Pinterest Brand Guidelines](https://business.pinterest.com/brand-guidelines/) | `P-Badge-Black-RGB.eps` from the linked Pinterest Logo asset collection; converted to SVG without redrawing |
| Mastodon | [Mastodon Brand Toolkit](https://joinmastodon.org/branding) and [trademark policy](https://joinmastodon.org/trademark) | Black mark, [`logo-black.svg`](https://joinmastodon.org/logos/logo-black.svg) |
| WhatsApp | [Meta Brand Resource Center](https://www.meta.com/en-gb/brand/resources/whatsapp/whatsapp-brand/) | `Digital_Glyph_Black_RGB_2026.svg` from the official logo pack |
| Discord | [Discord Brand Assets](https://discord.com/branding) | `Discord-Symbol-Black.svg` from the official black symbol download |
| Spotify | [Spotify Design & Branding Guidelines](https://developer.spotify.com/documentation/design) | `Primary_Logo_Black_RGB.svg` from the official 2024 icon download; uniformly scaled and centered |
| Vimeo | [Vimeo Media Kit](https://vimeo.com/press/media-kit) | `Logo - Lettermark - Black.svg` from the linked official icon folder |
| Reddit | [Reddit Brand System](https://reddit.lingoapp.com/s/Logo-d9x3n2/?kit=Brand-foundation-oYYL4W) and [social sharing guidance](https://reddit.lingoapp.com/s/Social-PXzmWE/?kit=Brand-foundation-oYYL4W) | `Reddit_Icon_2Color.svg`, current simplified mark; white areas converted to transparent negative space for the monochrome font |
| Telegram | [Bootstrap Icons v1.13.1](https://github.com/twbs/icons/blob/v1.13.1/icons/telegram.svg), checked against [Telegram’s official logo pack](https://telegram.org/tour/screenshots) | Monochrome circular mark, uniformly scaled and centered |
| Substack | [Bootstrap Icons v1.13.1](https://github.com/twbs/icons/blob/v1.13.1/icons/substack.svg) and [Substack Brand Guidelines](https://substack.com/brand) | Monochrome mark, uniformly scaled and centered |

These marks are supplied in monochrome. Pinterest’s circular badge must stay intact and link to the relevant Pinterest profile with a call to action; static uses must identify the account. Use the owners’ approved monochrome colors rather than applying arbitrary theme colors. Threads requires clear space of one quarter of the mark’s width. Mastodon’s toolkit specifies 36px clear space and using the mark where the brand is established; Discord’s symbol likewise needs clear brand context and is for digital use. WhatsApp allows scaling but prohibits changing the design or colors. Refer to the source guidance for complete conditions.

The icon font inherits `currentColor`. Use an approved brand color in the consuming interface; WhatsApp’s supplied black is `#111b21`.

Spotify’s artwork is 21px high within the 24px canvas; render this icon at 24px or larger so the mark meets its 21px digital minimum. Allow clear space of at least half the mark’s height. Use the icon alone only when space is limited or the Spotify brand is already established. Spotify specifies black on light backgrounds and white on dark backgrounds.

Vimeo’s lettermark must identify Vimeo without implying endorsement. Reddit prefers its full-color icon for social sharing; use the simplified version when the application cannot support full color, and follow its color rules. Telegram permits logos for relevant article illustrations and sharing controls without implying official representation. Substack prohibits changes to its logo’s color or proportions and requires surrounding white space; choose the appropriate official asset when an application needs a treatment beyond this monochrome glyph.

The Figma components follow the library’s existing convention: hidden editable `Artwork` uses Primary, and the visible flattened vector uses Text. These bindings support authoring and theme previews; they do not authorize arbitrary brand colors in published designs.

### Bootstrap Icons attribution

The Telegram and Substack SVG paths are derived from Bootstrap Icons v1.13.1. Their source and optimized SVGs retain the following license, which also applies to those paths in the catalog and generated font:

```text
The MIT License (MIT)

Copyright (c) 2019-2024 The Bootstrap Authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

