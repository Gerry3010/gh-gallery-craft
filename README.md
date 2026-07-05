# GH Gallery for Craft CMS

A high-performance **image & video gallery** for Craft CMS 5 — responsive grid or
CSS masonry, a native-`<dialog>` lightbox with swipe, slideshow, zoom, fullscreen
and per-item video playback. Powered by the proprietary [`gh-gallery`] web
component (Lit + Swiper, ~45 KB gzip, ships pre-built inside this plugin).

> Development home: private Bitbucket repo `Gerry3010/gh-gallery-craft`.
> Public releases (for the Craft Plugin Store) are published to
> `github.com/Gerry3010/gh-gallery-craft`.

## What you get

- A **`Gallery` field** — curate images and videos; render with `{{ entry.myGallery }}`.
- A **Twig function** — `{{ ghGallery(assets, options) }}` for full per-call control.
- On-the-fly, WebP image transforms + `srcset`; automatic **video posters**.
- One shared lightbox across all galleries on a page; deep-linkable slides.

## Requirements

- Craft CMS **5.0+**
- PHP **8.2+**

## Installation

```bash
composer require gerry3010/gh-gallery-craft
php craft plugin/install gh-gallery
```

## License

Commercial. See [`LICENSE.md`](LICENSE.md). The bundled `gh-gallery` web component
is proprietary; bundled third-party libraries (Swiper — MIT, Lit — BSD-3-Clause)
retain their notices.

[`gh-gallery`]: https://bitbucket.org/Gerry3010/gh-gallery-revamped
