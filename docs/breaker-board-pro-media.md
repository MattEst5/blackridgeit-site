# Breaker Board Pro media replacement plan

The pre-launch landing page intentionally uses labeled product-media slots instead of invented UI. Replace each slot with a real Breaker Board Pro capture after the release-candidate interface is locked.

## Required media

| Page slot (`data-media-slot`) | Intended file | Capture requirements |
| --- | --- | --- |
| `hero-portrait-fill-board` | `images/breaker-board-pro-obs-fill-board.webp` | A polished 1080 × 1920 OBS scene with the portrait Fill Board visible and the cards/camera area still dominant. Use only fictional, owned, or licensed artwork. Suggested alt: “Breaker Board Pro Fill Board shown as a portrait OBS overlay during a sports card break.” |
| `break-desk-control-interface` | `images/breaker-board-pro-break-desk.webp` | Wide Break Desk capture at 1600 × 900 or larger, showing a realistic prepared break with no customer names, account data, license data, or other private information. Suggested alt: “Breaker Board Pro Break Desk with fill, trade, and camera controls.” |
| `fill-board` | `images/breaker-board-pro-fill-board.webp` | Clean Fill Board product capture showing a mix of Available and Sold states. Suggested alt: “Breaker Board Pro Fill Board showing available and sold teams.” |
| `trade-board` | `images/breaker-board-pro-trade-board.webp` | Trade / Assignment Board capture showing readable fictional buyer and team assignments. Suggested alt: “Breaker Board Pro Trade Board with fictional buyer and team assignments.” |
| `camera-mode` | `images/breaker-board-pro-camera-mode.webp` | Camera mode capture with the camera frame and at least one persistent or timed graphic visible. Do not use identifiable customer video. Suggested alt: “Breaker Board Pro Camera mode with a persistent broadcast status.” |
| `portrait-stream-mockup` | `images/breaker-board-pro-portrait-card-break-overlay.webp` | Mobile/portrait stream composition based on a real 1080 × 1920 output. It may be presented in a device frame, but the BBP screen itself must be a real capture. Suggested alt: “Portrait sports card break stream with a Breaker Board Pro team overlay.” |
| `short-product-demo` | `media/breaker-board-pro-demo.mp4` and `images/breaker-board-pro-demo-poster.webp` | A short, captioned setup → fill → trade → rip walkthrough using the real product. Keep audio muted by default and do not autoplay audio. |

## Social/share image

Create `images/breaker-board-pro-social-share.webp` at approximately 1200 × 630 for Open Graph and Twitter metadata. It should combine real Breaker Board Pro branding with an authentic, legible product view; do not manufacture an interface or use unlicensed league/team art. The current logo-only social image is an acceptable pre-launch fallback, not the permanent share asset.

## Export guidance

- Prefer WebP for screenshots and the demo poster.
- Export screenshots at 2× their final display size when practical, then compress without making interface text soft.
- Aim for roughly 250 KB or less per screenshot when the result remains legible; use a larger budget for the hero only if necessary.
- Include explicit `width` and `height` attributes when replacing placeholders with `<img>` elements.
- Keep the above-fold hero image eager-loaded and consider `fetchpriority="high"`; use `loading="lazy"` for below-fold screenshots.
- Write concise alt text for the visible workflow or state, not the filename. Use the suggested text only when it accurately matches the final capture, and do not repeat search phrases or product terms unnaturally.
- Use only BlackRidge-owned, fictional, or properly licensed logos and artwork. Official league and team logos are not bundled with Breaker Board Pro and should not appear in public marketing media without established rights.
- Do not expose license keys, local file paths, email addresses, customer names, or other private data.

## Demo and structured-data follow-up

Once the real short demo is public, add a crawlable title, summary, captions, and transcript or step-by-step companion text near the video. Then evaluate `VideoObject` JSON-LD using only verified facts such as the final name, description, thumbnail URL, upload date, duration, and content or embed URL. Do not add placeholder video markup before those assets and facts exist.

The existing product wordmark is stored at `images/breaker-board-pro-logo.png` and is already used by the page and social metadata.
