# Breaker Board Pro media replacement plan

The pre-launch landing page intentionally uses labeled product-media slots instead of invented UI. Replace each slot with a real Breaker Board Pro capture after the release-candidate interface is locked.

## Required media

| Page slot (`data-media-slot`) | Intended file | Capture requirements |
| --- | --- | --- |
| `hero-portrait-fill-board` | `images/bbp-hero-fill-board-obs.webp` | A polished 1080 × 1920 OBS scene with the portrait Fill Board visible and the cards/camera area still dominant. Use only fictional, owned, or licensed artwork. |
| `break-desk-control-interface` | `images/bbp-break-desk.webp` | Wide Break Desk capture at 1600 × 900 or larger, showing a realistic prepared break with no customer names, account data, license data, or other private information. |
| `fill-board` | `images/bbp-fill-board.webp` | Clean Fill Board product capture showing a mix of Available and Sold states. |
| `trade-board` | `images/bbp-trade-board.webp` | Trade / Assignment Board capture showing readable fictional buyer and team assignments. |
| `camera-mode` | `images/bbp-camera-mode.webp` | Camera mode capture with the camera frame and at least one persistent or timed graphic visible. Do not use identifiable customer video. |
| `portrait-stream-mockup` | `images/bbp-portrait-stream.webp` | Mobile/portrait stream composition based on a real 1080 × 1920 output. It may be presented in a device frame, but the BBP screen itself must be a real capture. |
| `short-product-demo` | `media/bbp-demo.mp4` and `images/bbp-demo-poster.webp` | A short, captioned setup → fill → trade → rip walkthrough. Keep audio muted by default and do not autoplay audio. |

## Export guidance

- Prefer WebP for screenshots and the demo poster.
- Export screenshots at 2× their final display size when practical, then compress without making interface text soft.
- Aim for roughly 250 KB or less per screenshot when the result remains legible; use a larger budget for the hero only if necessary.
- Include explicit `width` and `height` attributes when replacing placeholders with `<img>` elements.
- Keep the hero image eager-loaded; use `loading="lazy"` for below-fold screenshots.
- Write alt text for the visible workflow or state, not the filename.
- Use only BlackRidge-owned, fictional, or properly licensed logos and artwork. Official league and team logos are not bundled with Breaker Board Pro and should not appear in public marketing media without established rights.
- Do not expose license keys, local file paths, email addresses, customer names, or other private data.

The existing product wordmark is stored at `images/breaker-board-pro-logo.png` and is already used by the page and social metadata.
