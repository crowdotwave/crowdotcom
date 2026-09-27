---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

# Surface: homepage (index.html)

Mode: Persuade. Audience: small business owners across Canada, mostly on a phone, often late after closing. Action: try a live demo, then send a written enquiry. Proof: the Nith Valley and trainer app recordings, live demo links, the memorial site. Constraints: PRODUCT.md (written-only contact, no prices, no invented claims, no em dashes, BRAND constant, [DECIDE] placeholders).

## Direction contract

THESIS: Loyalty drawn as light at a cloud's edge. A client's relationship is a band of colour that forms with each visit, runs vivid while they keep coming, and quietly disperses when they drift. Refuses the category default of a dark page with one neon accent and glowing cards.

OWN-WORLD: A noctilucent summer night over the prairie. Deep night-blue ground, silver-white cloud body, colour only at hairline edges in mint, rose and electric blue, with violet reserved for the active band and the one action. One humanist sans at hairline weight for display, regular for text. No cards with icons, no kickers, no glow halos; thin rules and generous dark space.

STORY: The visitor sees their clients as light that stays or fades, understands that the drifting ones can be caught and brought back, tries the real apps, and writes in.

FIRST VIEWPORT: A generated night sky fills the screen; a live iridescent cloud edge drifts across the upper right. Left, at hairline weight and large scale: "Loyalty that brings your clients back." One line under it, then "Try the live demo" as the violet-edged primary action and "Get in touch" beside it. Lower right, a small observation panel prints a sample client's points history line by line.

FORM: Iridescent cloud edge, a catalog challenger (clouds-storms-auroras-iridescent-cloud-edge) the user adopted with the steer "dark version", rendered as noctilucent cloud; not on the grounded list; seed key ce14b79e. Signature interaction: "Who is drifting" shows sample clients as edges in forming, vivid, dispersing and absent states; sending a note re-forms the band.

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance

## Finish review

Run in-thread (degraded path: no separate reviewer agent was spawned), against desktop 1440 and mobile 390 renders in `.impeccable/review/`.

- Fixed: on phones the cloud ribbon crossed the lede. It is now held in a pixel-measured strip above the headline.
- Fixed: the phone frames carried an ice-tinted shadow (detector `dark-glow`). Now a neutral drop.
- Accepted: detector `cramped-padding` on the hairline-ruled rows (clients, offers, versus table, section rules). These are open rules with vertical padding, not boxed containers.
- Accepted: detector `tight-leading` on the display and headline sizes (0.98 and 1.04 by design; body is 1.65).
- Checked: no console errors, no horizontal scroll at 390, "Send a note" updates the edge and status line, the observation log advances, the form stays disabled until the Formspree id is set, no em dashes, no email address, six `[DECIDE]` markers.
- Rasters: the only shipped rasters are the two recording posters, frames captured from the demo recordings of the real apps on invented data.

Verdict: ship as a preview for Chris to compare against `homepage-dark`.
