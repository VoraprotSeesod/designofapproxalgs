# Approx Lab artwork

The complete website is `../../index.html`. Both original PNGs and all fonts are embedded in that HTML as data URIs. Only the HTML is needed to use or share the offline lesson; these source assets are kept for future editing.

Created with the built-in **ImageGen** tool, using exactly one generation request per asset, without edits or retries. Original generated pixels and alpha are preserved.

- `approx-mascot.png`: 1254 × 1254 RGBA, original math-adventurer mascot.
- `approx-logo.png`: 1536 × 1024 RGBA, original APPROX LAB wordmark. The logo includes a translucent white glow around the sticker contour.
- `fonts/`: Itim Regular and Mali Regular/Bold from the official Google Fonts repository, together with their SIL Open Font License notices. The licenses are also embedded in an HTML comment in the standalone website.

The user supplied VchiBan and VTuberized Logos as visual direction. No artwork or brand identity was copied from those websites.

## Exact mascot prompt

```text
Use case: stylized-concept
Asset type: original transparent mascot raster illustration for APPROX LAB, a Thai interactive approximation-algorithms learning website.
Primary request: One cheerful original anime/VTuber math-adventurer adult female character. Oversized violet hair in lively twin tails with cyan tips, expressive teal eyes, white and cyan futuristic varsity jacket, little gold approximation-symbol hairclip. Holding a pen like a magic wand and a small tablet displaying simple connected graph nodes, playful confident peace-sign pose.
Style/medium: Clean premium hand-drawn manga linework and crisp cel shading, charming lively expression, polished professional character art.
Color palette: cyan, hot pink, lime yellow, purple.
Composition/framing: Single centered character, approximately 1024 square portrait-ish composition; full chibi three-quarter body with all depicted anatomy, hair and props fully within frame, generous safe margins. Clear compact silhouette readable in a 250px side panel and a 210px-high course header.
Scene/backdrop: Genuinely transparent background with preserved alpha, no white rectangle, no checkerboard baked into image.
Constraints: Original character only. No lettering, no watermark, no existing character. Only one character, anatomically coherent hands and arms. Transparent isolated asset.
```

## Exact logo prompt

```text
Use case: logo-brand
Asset type: Original VTuber-style hand-lettered transparent raster logo for APPROX LAB, a Thai interactive approximation-algorithms learning website.
Text (verbatim): "APPROX LAB"
Primary request: Elaborate yet clearly legible candy typography. APPROX is the large top line, LAB beneath. Spell APPROX exactly A-P-P-R-O-X and LAB exactly L-A-B. Bold purple outlines and white outer sticker contour, cyan-to-violet letters with hot-pink and sunny-yellow accents. Integrate a small approximation symbol and graph-node motifs with sparkle accents.
Style/medium: Polished Japanese streamer/game logo aesthetic, premium hand-lettered brand art, crisp illustrated edges.
Composition/framing: Centered horizontal composition approximately 3:2, generous safe margins, all artwork within frame.
Scene/backdrop: Genuinely transparent background with preserved alpha; the white outer sticker contour belongs only around the logo shape, with transparent surroundings and no white rectangular backdrop. No checkerboard baked into image.
Constraints: No other lettering, no existing brands, no watermark. Exactly one logo, exactly the text APPROX LAB.
```

## Validation

The lesson data and interactive logic were checked in Node, including all ten lesson flows, thirty flashcards and thirty quiz answers; first-answer locking, retries, badge conditions, restoration, corrupted/blocked storage, and reset; and exact numerical checks for the set-cover, scheduling, knapsack and MAX CUT examples. PNG alpha and embedded image decoding were checked. Browser screenshots or layout inspection were not performed.
