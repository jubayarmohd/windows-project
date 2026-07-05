# Immersa Builder Third-Party Licenses

Immersa Builder is distributed under the GNU General Public License v2 or later. This file documents every third-party asset, inline SVG icon source, and reset foundation included in the theme package.

## Inline SVG Social Icons

### Feather Icons

Location: `inc/footer-render.php`

Used icons: Facebook, Instagram, LinkedIn, YouTube, and GitHub SVG paths.

Copyright: Copyright (c) 2013-2023 Cole Bemis and Feather contributors.

License: MIT License.

License URI: https://github.com/feathericons/feather/blob/master/LICENSE

Source: https://github.com/feathericons/feather

Notes: SVG paths are embedded inline so the theme does not require an icon font or remote icon request.

### Simple Icons

Location: `inc/footer-render.php`

Used icons: X / Twitter, Facebook, Insta, LinkedIn, TikTok, Pinterest, and WordPress SVG marks.

Copyright: Simple Icons Contributors.

License: CC0 1.0 Universal.

License URI: https://github.com/simple-icons/simple-icons/blob/develop/LICENSE.md

Source: https://github.com/simple-icons/simple-icons

Notes: SVG paths are embedded inline so the theme does not require an icon font or remote icon request.

Social-network names and marks are trademarks of their respective owners. They are used only to identify configured social-link destinations.

## CSS Reset Foundation

### Modern CSS Reset

Location: reset foundation at the top of `assets/css/base.css`.

Copyright: Copyright (c) 2019 Andy Bell and contributors.

License: MIT License.

License URI: https://github.com/hankchizljaw/modern-css-reset/blob/master/LICENSE

Source: https://github.com/hankchizljaw/modern-css-reset

Notes: Immersa Builder uses an adapted subset as the base reset. The theme adds its own typography, layout, WordPress, WooCommerce, and responsive rules after the reset foundation.

## Theme-Owned Material

Theme PHP, CSS outside the documented reset foundation, JavaScript, block patterns, template parts, and original SVG modifications are Copyright 2026 Codefreex and licensed GPL-2.0-or-later.

`screenshot.png` is Copyright 2026 Codefreex and licensed GPL-2.0-or-later. It is a self-created Immersa Builder UI preview made for this distribution and contains no stock photo, externally sourced image, or imported raster asset.

## Runtime Dependencies Not Bundled

The Customizer preview declares `jquery` as a dependency. WordPress core supplies it at runtime; no jQuery file is included in this theme package. WordPress is licensed under GPL-2.0-or-later.

The theme uses operating-system font stacks only. It does not include font files and does not request remote web-font files.
