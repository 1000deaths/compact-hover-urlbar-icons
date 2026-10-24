# Compact Hover Urlbar Icons

A [Sine](https://github.com/CosmoCreeper/Sine) mod for Zen Browser.

While **compact mode** is on, the address bar's icons — copy link, site settings, zoom level, and the other page-action, identity and pinned-extension buttons — stay hidden and fade in only while you hover the address bar. Outside compact mode nothing changes.

They also stay visible while a panel opened from one of them is showing, and on an empty new tab (matching Zen's own behaviour). Opening the floating URL bar is untouched.

## Install

1. In Zen, open Settings → Sine.
2. Add the mod by entering the repository: `1000deaths/compact-hover-urlbar-icons`
3. Enable compact mode.

## Notes

- Built against Zen's current source: it targets `#zen-copy-url-button`, `#zen-site-data-icon-button`, `#urlbar-zoom-button`, `.urlbar-page-action`, `.identity-box-button` and `.unified-extensions-item` inside `#urlbar`, gated on `:root[zen-compact-mode="true"]`.
- Respects `prefers-reduced-motion` (no fade).
