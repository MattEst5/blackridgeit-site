# Breaker Board Pro product-page media

The v1.0.0 page uses six real owner-supplied screenshots. The visual story is Break Desk → real-world portrait stream → Fill → Trade → live graphics → customer artwork. The owned BBP wordmark is the hero identity and the Open Graph/Twitter image. Windows checkout remains pending; no checkout or installer is exposed.

## Production assets

All production files live in `images/breaker-board-pro/`. Originals remain in the local, uncommitted `incoming-bbp-media/` folder. Crop coordinates are `(left, top, right, bottom)` in original pixels, with right/bottom exclusive. No UI content was altered, composited, or generated. No image was resized.

| Production filename | Original filename | Dimensions (px) | Bytes | Transformation |
| --- | --- | --- | ---: | --- |
| `breaker-board-pro-break-desk.webp` | `Screenshot 2026-10-15 185544.png` | 1474 × 793 | 197,878 | Crop (0, 0, 1474, 793); lossless WebP |
| `breaker-board-pro-live-portrait.webp` | `Screenshot 2026-10-15 185142(1).png` | 670 × 1018 | 83,788 | Crop (0, 170, 670, 1188); WebP quality 92 |
| `breaker-board-pro-fill-board.webp` | `Screenshot 2026-10-15 190047.png` | 1153 × 475 | 337,012 | No crop; lossless WebP |
| `breaker-board-pro-trade-board.webp` | `Screenshot 2026-10-15 185030(1).png` | 611 × 251 | 118,566 | Crop (40, 179, 651, 430); lossless WebP |
| `breaker-board-pro-live-status.webp` | `Screenshot 2026-10-15 185652.png` | 627 × 130 | 48,450 | Crop (36, 412, 663, 542); lossless WebP |
| `breaker-board-pro-logo-pack-demo.webp` | `Screenshot 2026-10-15 190120.png` | 1147 × 472 | 397,654 | No crop; lossless WebP |

Five screenshots use lossless WebP to preserve interface text. The portrait context image uses quality-92 WebP. The two full-board lossless assets exceed the earlier approximate 250 KB target to preserve sharp text and artwork. Total production screenshot weight: 1,183,348 bytes.

## Placement and crop intent

- **Break Desk:** the primary wide screenshot. Its crop retains branding, break setup, metadata, and sample team/buyer/price controls. The right-side output preview is excluded because its breaker header contains a small league mark; the crop also removes the transient Logo Pack toast. The caption describes the full Break Desk workflow, while the alt text describes only the visible crop.
- **Portrait live-selling use:** retained as the main in-use context image. The crop removes browser chrome and the upper breaker-brand header containing a league mark. The clean abbreviation Fill Board, physical products, and marketplace controls remain in their authentic vertical arrangement. Product packaging is incidental real-world context, not included digital artwork or a partnership claim.
- **Fill Board:** the clean abbreviation-based board is the default public board example. Retained without cropping. It is a Random Team board; the page does not claim this capture shows mixed Sold/Available states.
- **Trade Board:** cropped tightly to the actual board, excluding the separate brand header, marketplace chrome, and physical products. The assignments are the owner's supplied fictional demonstration data.
- **Live status:** retained. Cropped to the actual STASH OR PASS graphic, without recreating the interface. The adjacent copy explains persistent statuses, custom statuses, timed alerts, and ticker messaging.
- **Logo Pack demonstration:** retained only as the sixth gallery example. It is the one specifically owner-approved screenshot intentionally demonstrating imported third-party team/league marks. It is never hero, primary identity, Open Graph, or Twitter imagery.

All screenshots have explicit dimensions and meaningful alt text, use lazy loading, preserve their natural aspect ratio, and link to the final WebP at full size for closer inspection. Portrait media keeps its vertical character and a bounded desktop width. The full-size Logo Pack link is described by its visible page disclosure.

## Narrow artwork approval

One owner-approved Logo Pack demonstration screenshot may contain customer-supplied third-party marks when accompanied immediately by the approved licensing/non-affiliation disclosure. This is a narrow marketing-use instruction, not a statement that a disclaimer grants any intellectual-property rights.

The following disclosure is visible directly beneath the Logo Pack image, before its feature caption, at readable desktop and mobile sizes:

> Customer-supplied artwork shown for demonstration. Team and league marks are trademarks of their respective owners. BlackRidge IT does not own or license the third-party marks shown and is not affiliated with or endorsed by MLB or its clubs. Official league and team logos are not included with Breaker Board Pro. Customers are responsible for having rights to artwork they import.

Official league/team logos are **not included** with Breaker Board Pro. Customers are responsible for rights to imported artwork. BlackRidge must not imply ownership, licensing, sponsorship, endorsement, or affiliation, or offer downloadable official logo packs. Third-party marks must not be used in hero or social imagery without separate approval. The original screenshots are working inputs, not distributable Logo Packs.

## Marketplace context

Marketplace UI may appear in the narrowly contextual portrait screenshot. It does not imply partnership, endorsement, sponsorship, native platform functionality, or API integration. Marketplace screenshots are not automatically suitable for hero/social imagery. No marketplace UI is used in the hero or social metadata.

Visible nearby wording:

> Breaker Board Pro operates independently alongside live-selling platforms. Whatnot is a trademark of its respective owner. BlackRidge IT is not affiliated with or endorsed by Whatnot. Direct Whatnot API integration is not currently available.

## Camera and video

Camera and Hidden remain marketed as current presentation modes in text. There is no dedicated Camera Mode image, empty card, or required Camera screenshot. A product video is not part of this page: the reserved demo section, fake play control, and video placeholder are removed. No video asset or `VideoObject` structured data is required or included.

## Metadata and delivery

- Keep `images/breaker-board-pro-logo.png` as the owned hero identity and social image.
- SoftwareApplication states version 1.0.0, Windows, BlackRidge IT, verified capabilities, $59.99 one-time launch pricing, $79.99 regular pricing, and pending purchase availability. The visible FAQ and FAQPage answers match.
- No purchasable `Offer`, download URL, ratings/reviews, release date, price-expiry date, or `VideoObject` is asserted while checkout is pending.
- Source screenshots remain excluded through checkout-local `.git/info/exclude`; stage only intended production assets and source changes. Never delete the owner's originals as part of page completion.
