# Saroki's Dynamic Pricing

A pitch package for a 90-day dynamic pricing pilot at Saroki's Crispy Chicken & Pizza, 10 Mile & Dequindre, Warren MI. The idea: convenience-store prices that react to time of day, weather, and local events inside owner-approved guardrails, inspired by McDonald's 2019 acquisition of Dynamic Yield.

## Files

- `demo.html` - Interactive demo of the dynamic pricing engine. All data in it is sample data, clearly labeled, for demonstration only.
- `deck.md` - Slide-by-slide pitch deck content (9 slides) for the meeting with the Saroki family.
- `research.md` - Verified research with source links: the McDonald's/Dynamic Yield acquisition, the Wendy's 2024 cautionary tale, and light Saroki's corporate facts.

## How to view the demo locally

Open `demo.html` in any web browser. No build step, no server needed. Double-click the file, or serve the folder with any static server:

```
python3 -m http.server 8000
```

then open http://localhost:8000/demo.html

Hosted artifacts: pitch deck file `workspace/your_files/sarokis-pitch-deck/sarokis-pitch-deck.pptx` (artifact slug `sarokis-pitch-deck`), and interactive demo slug `saroki-s-dynamic-pricing-demo` (web_static, opened and shared from its artifact card in Muse).

## Continuing this work

This repo is the single source of truth for the project. If you are another AI picking this up:

1. Edit the source files directly: `research.md` for facts and citations, `deck.md` for pitch content, `demo.html` for the interactive engine. Keep the plain-punctuation style (no em dashes) and the SAMPLE DATA labeling in the demo.
2. Do not invent Shafayet's sales data, store figures, or research claims. Every number in `research.md` needs a source link; every unknown belongs in a [PLACEHOLDER].
3. When your changes are done, hand the result back to Shafayet's Muse to rebuild and redeploy the hosted artifacts. Do not publish or push anything on your own.
