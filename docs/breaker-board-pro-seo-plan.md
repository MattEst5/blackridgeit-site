# Breaker Board Pro SEO discovery plan

This plan maps real search language to useful page content without turning the landing page into a keyword list. Breaker Board Pro remains a pre-launch product, and every search-facing statement must stay within the product facts shown on the page.

## Search-intent map

| Intent family | Search language evaluated | Reader's job | Page destination and treatment |
| --- | --- | --- | --- |
| Core software | sports card breaker software; sports card break software; trading card break software; card breaking software; breaker software; sports card breaker tools | Find software built for operating and presenting a live card break | Keep the concise product title and H1. Use “sports card breaker software” once in the hero and explain the actual Break Desk, board, and broadcast workflow in the problem and feature sections. The remaining variants are context, not phrases to repeat verbatim. |
| Overlay and OBS | sports card break overlay; sports card breaker overlay; OBS overlay for card breakers; card break OBS overlay; live break overlay; sports card stream overlay; sports card stream graphics; vertical OBS overlay; portrait card break overlay | Understand how BBP graphics enter OBS and fit a vertical stream | Use “OBS overlay” in visible copy, explain local Browser Source URLs, and identify the tested portrait and horizontal canvases. Reserve descriptive screenshot and video assets for the real-media pass. |
| Break and team boards | sports card break board; Whatnot break board; breaker team board; card break team board; team availability board; sold team board; team assignment board; buyer assignment board | Track open teams, sold teams, and assignments without rebuilding graphics | Map these needs to the Fill Board, Trade / Assignment Board, and Set up → Fill → Trade → Rip workflow. Describe states and jobs instead of listing query variants. |
| Whatnot workflow | Whatnot breaker overlay; Whatnot card breaker overlay; Whatnot break board; Whatnot seller tools for card breakers; OBS overlay for Whatnot card breaks | Run BBP alongside a Whatnot sale and understand the integration boundary | Explain that Whatnot handles the marketplace and sale today while BBP independently handles the local board and OBS presentation. Keep the approved integration FAQ, the conditional future API direction, and the non-affiliation statement. Do not imply current API access, certification, or endorsement. |
| Break formats | PYT break board; Pick Your Team break software; Pick Your Team overlay; Random Team break board; Random Team assignment board | Run the board for a Pick Your Team or Random Team break | Explain both formats in the workflow and feature sections. State that Random Team results are generated externally and entered into BBP for assignment and presentation. |
| Baseball / MLB | baseball card break board; MLB break board; MLB card break overlay | Determine whether BBP supports baseball team breaks | Use one practical sports-section example and the league-use FAQ. Use MLB descriptively; do not imply affiliation or bundled official artwork. |
| Football / NFL | football card break board; NFL break board; NFL breaker overlay | Determine whether BBP supports football PYT and Random Team breaks | Use one practical sports-section example and the league-use FAQ, with the same rights and non-affiliation boundary. |
| Basketball / NBA | basketball card break board; NBA break board | Determine whether BBP supports basketball team breaks | Cover naturally in the sports section and league-use FAQ. |
| Hockey / NHL | hockey card break board; NHL break board | Determine whether BBP supports hockey team breaks | Cover naturally in the sports section and league-use FAQ. |
| Other formats | NASCAR break board; soccer card break board | Determine whether BBP can present driver, team, player, division, or spot formats | Explain NASCAR, soccer, and Custom as flexible formats in the sports section rather than creating thin sport-specific pages. |

## Landing-page decisions

- Retain the current title and H1: they are descriptive, concise, and already cover the product, OBS, team-board, and audience intent.
- Let visible copy carry related vocabulary through explanations of actual tasks. Do not add a meta-keywords tag, hidden copy, or repetitive query blocks.
- Keep the approved activation and Whatnot integration answers unchanged in visible HTML and JSON-LD.
- Keep commerce claims pre-launch. Do not add an `Offer`, availability, checkout URL, rating, or review until the corresponding facts exist visibly and can be verified.
- Retain valid `SoftwareApplication` and visible-FAQ-aligned `FAQPage` data, but do not treat FAQ markup as a Google rich-result tactic. Add only an accurate breadcrumb matching the visible hierarchy.

## Future people-first content cluster

Do not publish these pages until real product captures, first-hand steps, and a release-candidate workflow are available.

| Future guide | Distinct reader problem | Required first-hand value |
| --- | --- | --- |
| How to Set Up an OBS Overlay for Sports Card Breaks | Add and size BBP Browser Sources in OBS | Real OBS scene screenshots, exact canvas settings, setup steps, and troubleshooting notes |
| How to Run a PYT Break Board in OBS | Move a Pick Your Team break from open spots to confirmed assignments | A complete fictional PYT example, Fill Board and Trade Board captures, and operator checklist |
| How to Run Random Team Assignments in Breaker Board Pro | Bring externally randomized results into BBP accurately | A clearly documented external-randomization boundary, import/entry example, confirmation steps, and screenshots |
| Whatnot Card Break OBS Setup Guide | Arrange a portrait broadcast in which Whatnot runs the sale and BBP runs presentation | A real 1080 × 1920 scene, practical phone/camera/board layout, and explicit current-integration and non-affiliation boundaries |
| Baseball Card Break Team Board Guide | Configure common baseball PYT/team-board workflows | A real baseball-format example using owned or fictional artwork, format decisions, and rights guidance |
| Football Card Break Team Board Guide | Configure football PYT or Random Team team-board workflows | A distinct football-format example, assignment handling, and real captures—not a league-name swap of the baseball guide |

If the sport guides cannot provide meaningfully different workflows and evidence, consolidate them into one multi-sport team-board guide instead of publishing near-duplicate MLB, NFL, NBA, and NHL doorway pages.

## Post-publication indexing checklist

1. Publish through the normal production workflow and verify that `https://blackridgeit.net/breaker-board-pro.html` returns a successful HTML response.
2. Inspect the canonical URL in Google Search Console, confirm the rendered page and declared canonical, and request indexing.
3. Submit or reconfirm `https://blackridgeit.net/sitemap.xml` in Google Search Console.
4. Monitor Search Console indexing, impressions, clicks, and actual query language. Use observed questions and workflows—not speculative keyword variants—to prioritize future guides.
5. Verify `blackridgeit.net` in Bing Webmaster Tools and submit the same sitemap.
6. Inspect the product URL in Bing Webmaster Tools after publication.
7. Evaluate IndexNow for future additions and material updates. If adopted, host the ownership key securely and submit only changed URLs; do not commit private keys or credentials to this repository.

## Measurement and maintenance

- Review query and landing-page performance after enough impressions exist; avoid reacting to daily noise.
- Update copy when product capabilities or commercial facts change, keeping visible text and JSON-LD synchronized.
- Replace placeholder media only with real product captures, then follow `docs/breaker-board-pro-media.md` for filenames, alt text, dimensions, and loading behavior.
- Evaluate `VideoObject` only after a real public demo, thumbnail, duration, upload date, and crawlable supporting transcript or summary are available.

## Guidance references

- [Google: Creating helpful, reliable, people-first content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)
- [Google: Influencing title links](https://developers.google.com/search/docs/appearance/title-link)
- [Google: Controlling search snippets](https://developers.google.com/search/docs/appearance/snippet)
- [Google: Structured data introduction](https://developers.google.com/search/docs/appearance/structured-data/intro-structured-data)
- [Google: Breadcrumb structured data](https://developers.google.com/search/docs/appearance/structured-data/breadcrumb)
- [Google: Software application structured data](https://developers.google.com/search/docs/appearance/structured-data/software-app)
- [Google: Changes to FAQ rich results](https://developers.google.com/search/blog/2023/08/howto-faq-changes)
- [Bing Webmaster Tools: Sitemaps](https://www.bing.com/webmasters/help/sitemaps-3b5cf6ed)
- [IndexNow documentation](https://www.indexnow.org/documentation)
