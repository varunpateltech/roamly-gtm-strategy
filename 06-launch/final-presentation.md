# Final GTM Presentation — Roamly Groups

> Module 6 · Launch — ★ Final submission
>
> Assemble your six deliverables into one shareable presentation. The fastest way to a polished result is to generate it as a single, self-contained **HTML file** with any AI tool, then save it here as `final-presentation.html`.

## How to build it

1. Open the **[Presentation Prompt Builder](../../Modules/Module%206%20-%20Presentation%20Prompt%20Builder.html)** (or use the prompt below).
2. Get your deliverables in — the fast way: paste your **public GitHub repo link** into the *Quick-fill from your project repo* bar and it pulls these six markdown files automatically. Or paste them in by hand (Modules 1–5 + your individual insights).
3. Review and tidy the imported text, then copy the generated prompt into Claude, ChatGPT, Gemini — any LLM.
4. Save the returned file as `final-presentation.html` in this folder.
5. Open it in a browser to review, refine the content where needed, and submit your copy to the LMS within **7 days** of the course completing.

## The master prompt

```
You are an expert presentation designer. Create a single, self-contained HTML file
for my final Go-To-Market project presentation. It must run offline by opening the
file in a browser — all CSS and JS inline, no build step, no external assets.

DESIGN
- Full-viewport vertical scroll-snap deck: one <section> per slide, min-height:100vh.
- Dark navy theme (#07162C), white headings, light-grey body text, a blue accent (#3b82f6).
- Clean typography, subtle fade-in on scroll, a top progress bar, right-side nav dots,
  and arrow-key navigation. Professional and minimal — no stock images. Fully responsive.

STRUCTURE — one slide each, in this order:
1. Title — "[NAME] · Go-To-Market Final Project", product: Roamly Groups, today's date.
2. GTM Strategy — motion + rationale, target segment, one-pager summary.
3. Competitive Intelligence & Strategic Bet — battlecard highlights + the strategic bet.
4. Positioning — framework, finalized statement, and one-liner.
5. Messaging — three pillars (Value Prop, Capabilities, Evidence) per audience + AI asset.
6. Pricing Recommendation — model, packaging, and the validating research method.
7. Individual Insights — friction points, biggest "aha" moment, key takeaways.
8. Closing — a one-line summary of the GTM bet + thank you.

CONTENT — use exactly what I paste below; keep each slide tight and scannable (bullets > paragraphs).
--- GTM STRATEGY ---            <paste from 01-gtm-strategy/gtm-strategy.md>
--- COMPETITIVE INTEL & BET ---  <paste from 02-competitive-intel/battlecard-and-bet.md>
--- POSITIONING ---             <paste from 03-positioning/positioning.md>
--- MESSAGING ---              <paste from 04-messaging/messaging-and-asset.md>
--- PRICING ---                <paste from 05-pricing/pricing-recommendation.md>
--- INDIVIDUAL INSIGHTS ---     <paste from 06-launch/individual-insights.md>

OUTPUT — return only the complete HTML file in one code block, ready to save as index.html.
```

## Link to the published deck

[final-presentation.html](final-presentation.html) in this repo. Generated with Claude, using the exact master prompt above with all six deliverable files as content, then reviewed for accuracy against the source files. The AI asset image is embedded as a base64 data URI so the file stays fully self-contained and works offline.

**Design departure from the master prompt's default theme:** rather than the generic dark-navy-and-blue-accent look, the deck is styled as "The Shared Itinerary", a real ticket/boarding-pass visual language (ledger-cream cards, a perforated tear line on every slide, and a bottom "manifest" strip of stamp-style nav dots that fill in from pending to confirmed as the deck progresses), grounded specifically in the group-booking, organizer/guest, confirm-and-pay subject rather than a generic SaaS template. The content and structure still follow the master prompt exactly.
