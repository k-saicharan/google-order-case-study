# Project Log: Google Store Order Case Site

## 2026-06-30: Initial build

- Session: full case enrichment, role-hat audit, Gmail check, debrief (4 iterations), systemic solution design, site build
- Site built: `index.html` (6 system layers, 5 levers, timeline, pull quote, conclusion)
- Design v2: editorial redesign with DM Serif Display, dark hero, warm paper background, accent left borders on layer panels
- Status at build: Day 21, unresolved. Pixel not delivered. Specialist team silent. Klarna instalment 2 due 11 July (£179.67). Trade-in clock running.
- Open: Klarna dispute not yet triggered by Sai. Written Google complaint not yet sent.
- Vault source: `Void/Observations/Google Store Order Case/`

---

## 2026-06-30: Dashboard redesign for progressive disclosure

- Redesigned `index.html` to add accordions for the six layers and five failure levers.
- Embedded custom CSS grid transitions (`grid-template-rows: 0fr -> 1fr`) to allow smooth height animations without hardcoded bounds or jank.
- Added vanilla JS supporting single-open accordion behavior on the layer panels, and independent toggling on lever cards.
- Ensured findings and fix actions remain always-visible to highlight critical takeaways first.
- Results documented in `_antigravity/dashboard-redesign-less-wordy.result.md`.

---

## 2026-06-30: Dark Editorial Dossier Redesign

- Redesigned the visual theme to a premium, warm-toned Dark Editorial Dossier format (deep charcoal espresso paper background `#121115` with warm off-white cream typography `#ECE8E1`).
- Completely removed all digital "AI-looking" tech artifacts, including dot grids, neon glows, and barcode elements.
- Implemented natural, tactile dossier details:
  - An authentic, distressed red ink audit/debrief stamp (`OFFICIAL DEBRIEF // UNRESOLVED`).
  - Soft, realistic drop shadows on panels and cards to simulate physical paper sheets.
  - Clean solid timeline lines instead of digital dashed lines.
  - Underlined inline footnote style accordion links (`toggle-btn`) instead of blocky buttons.
- Cleaned up the codebase and project logs to strictly eliminate all em dashes, replacing them with semicolons, colons, or parentheses.

---

## 2026-06-30: Reversion to Original Visual Theme

- Discarded the dark dossier visual theme as per feedback.
- Reverted `index.html` fully back to the original visual identity (warm paper light background `#F5F3EE` with the dark hero banner `#0D0F14`).
- Maintained the progressive disclosure accordion feature and layout structure while restoring the original clean, light editorial styles.
- Kept the codebase and project logs completely free of em dashes.

---

## 2026-06-30: Premium Investigative Brief Redesign (V3)

- Implemented the Premium Investigative Brief design system as approved by the user.
- Refined the theme to add high-fidelity visual depth, texture, and responsive micro-interactions:
  - Added an organic cotton paper grain texture overlay (SVG noise filter) to make the sand background feel physically real.
  - Implemented 3D card lift hover translations and soft, realistic drop shadows on panels and cards.
  - Added a breathing, glowing pulse-ripple animation to the live unresolved badge.
  - Enabled fade-in and slide-up animations (transform and opacity transition) for expanded accordion bodies.
  - Embedded forensic tracking animations on the timeline (highlighting dates, scaling status dots, and coloring connector lines on hover).
  - Styled accordion toggles as elegant, underlined document links that scale chevron indicators on hover.
- Ensured all codebase files and project logs remain completely free of em dashes.

---

## 2026-07-01: X Outreach Strategy

- Researched X profiles worth tagging in the accountability post.
- Initial suggestion included Rick Osterloh (@rosterloh, SVP Platforms & Devices). User correctly pushed back: Osterloh owns the hardware product, not the Store, not the support chain, not the fulfillment operation. Wrong seat.
- Identified Ana Corrales (COO Google Consumer Hardware) as the right accountability target: she explicitly owns the Google Store as Google's first-party retail channel. Supply chain, order ops, post-purchase support all sit under her. No confirmed public X handle found.
- Final tag strategy: `@madebygoogle` (brand), `@GoogleUK` (UK market), `@KateAlessi` (Google UK MD, dormant but on record), `@9to5google` and `@androidauthority` (tech press; higher-leverage than executive tags when the exec has no active X presence).
- X post draft locked: three lines, factual, links to the site, lets the analysis do the work.

---

## 2026-07-01: Direct Email to Ana Corrales

- Identified `ana.corrales@google.com` as the most likely address from Google's confirmed email format pattern (firstname.lastname, ~33% usage). Alternative candidates: `a.corrales@google.com`, `acorrales@google.com`.
- Confidence assessed at ~60% before verification.
- Email draft: subject `Google Store: six-system operational gap, documented — Order GS.0190-9911-6648`. Body kept to four short paragraphs: framing (not a support escalation), the structural finding, the link, the three case reference numbers + Klarna deadline. No bullet points. Register: ops brief to a COO, not a customer complaint. User requested shorter version after first draft was too long; second draft delegates all analytical weight to the site.
- Email address verification via Hunter.io initiated at end of session (in progress).

---

---

## 2026-07-01: John (supervisor) reply, X DM content recovered, Promise Ledger built

- Verified new email in `7-9313000041414`: John, self-identified as an Order Management supervisor, replied 30 June 16:08 with a generic non-committal message; no RMA reference, no dispatch date. Sai pushed back same day asking for a concrete date.
- Recovered the actual `@madebygoogle` X DM content (screenshotted by Sai): Alex confirmed escalation, quoted "24-48 hrs," and stated future contact will come by email against the case ID Sai gave, which was the *original* case (`2-6444000041410`), not the active thread (`7-9313000041414`). So the X channel funnels back into the same email queue; it is not a parallel track.
- Cross-checked against primary Gmail sources (not the earlier secondary research transcripts) to get an exact count of every time Google has quoted a numbered turnaround window across the whole case: 4 confirmed instances (Joanne 16 Jun "24 hours"; Jen 26 Jun x2 "24-48 hours"; Alex 30 Jun X DM "24-48 hrs"). 3 of the 4 have already run past their own stated window; the 4th (X DM) opened 30 June and is still inside it. 6 further replies promised a follow-up with no number attached at all.
- Built a new site section, `#ledger` ("The Pattern, Counted"): a tally-mark visual (CSS, no images) showing 4 marks, 3 struck through in oxblood for broken promises, 1 unstruck in amber with a live pulse for the one still holding, backed by a dated quote-and-status list. Added two new timeline entries (30 Jun: John + X channel opens; 1 Jul Day 22: X resolves to the same queue). Added a "Promise Ledger" nav link.
- Verified in-browser via a local static server before calling it done (screenshots confirmed correct rendering, correct auto-updating Day 22 count, no layout breakage into the Evidence Key section below).
- **Correction to prior assumption:** the 2026-07-01 project log entries for "X Outreach Strategy" and "Direct Email to Ana Corrales" were drafts only. Checked Gmail sent folder (no message to any Corrales address) and Sai's X posts (nothing posted today) — neither has actually gone out. Flagged back to Sai rather than treated as done.

---

_Next entry: add when case status changes: Google responds, replacement dispatched, Klarna dispute opens, email verification result confirmed, the drafted Ana Corrales email or X post actually sends, or case closes._
