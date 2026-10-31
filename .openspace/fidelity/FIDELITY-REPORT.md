# Visual fidelity

Overall match: **25/100** — fonts, type sizes, spacing and each section measured in a browser on both sites, and how alike the pages look as pictures, each counted from what two unrelated pages score (0) to identical (100); the weaker of the two counts double, and so do the weakest page and device. How it's scored: docs/qa/import-fidelity.md.

**Next step:** The automatic move is rough (25/100): the words and pictures came across, but most of the design didn't. That's normal for custom-built sites. Claude can make it match closely: in Claude with the OpenSpace connector, use the finish-a-move prompt (or Studio's "Finish it with Claude"). It compares the old and new pages side by side and rebuilds what didn't come across, keeping every word and picture editable.

Scored two ways, side by side: **25/100 corrected**, 25/100 by the strict v3 scorer. The corrected score reads three things the strict one gets wrong (navigation in a header themed "brand", off-screen slides counted as columns, a picture-only band on a phone); the pages below list where it did.

Before auto-tuning: 25/100. What it changed:

- text on light sections #000000, as on the original (3 of 3 sections)
- heading on light sections #000000, as on the original (2 of 2 sections)

## / at 1440px — 20/100

Checks passed: 60% · screenshots 60% alike (two unrelated pages compare at about 55%).

Original: https://www.katieteague.com/home/  
Imported: / (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 2: present | freight-sans-pro 45.4px | not found | **differs** |
| Body font | Open Sans | Open Sans | same |
| Body text size | 17.7px | 14px | **differs** |
| Label font | freight-sans-pro | Mukta (close stand-in) | close (85%) |
| Buttons size | 21.2px | 21.2px | same |
| Buttons letter spacing and case | 0.02em, none | 0.02em, none | same |
| Navigation size | 14.3px | 14.3px | same |
| Navigation letter spacing and case | 0.01em, none | 0.01em, none | same |
| Site title size | 14.3px | 14.3px | same |
| Site title letter spacing and case | 0.01em, none | 0.01em, none | same |
| Button corners | 6.4px | 8px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Films for a more sane civilization. | 34 | Heading: freight-sans-pro 45.4px → Mukta 45.4px; Text: Open Sans 17.7px → Open Sans 14px; Text color: #000000 → #636363; Columns: 1 → 2; Image placement: center, 100% wide → none; Height: 7713px → 4811px |

What would close the gap:

- choices.typography.scale.body.size = 18
- Site Styles → choices.typography.label = { family: "freight-sans-pro" } (Google Fonts), or upload it in Site Styles → Your fonts.
- Fewer columns: merge them into one stack column.
- Adjust the stack column spans (image column) or the image's side.

## / at 390px — 21/100

Checks passed: 62% · screenshots 69% alike (two unrelated pages compare at about 65%).

Original: https://www.katieteague.com/home/  
Imported: / (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 2: present | freight-sans-pro 34.4px | not found | **differs** |
| Body font | Open Sans | Open Sans | same |
| Body text size | 17.1px | 14px | **differs** |
| Label font | freight-sans-pro | Mukta (close stand-in) | close (85%) |
| Buttons size | 19.2px | 19.3px | same |
| Buttons letter spacing and case | 0.02em, none | 0.02em, none | same |
| Button corners | 6.4px | 8px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Films for a more sane civilization. | 52 | Heading: freight-sans-pro 34.4px → Mukta 34.7px; Text: Open Sans 17.1px → Open Sans 14px; Text color: #000000 → #636363; Image placement: center, 100% wide → none; Height: 9287px → 6207px |

What would close the gap:

- choices.typography.scale.body.sizeMobile = 17
- Site Styles → choices.typography.label = { family: "freight-sans-pro" } (Google Fonts), or upload it in Site Styles → Your fonts.
- Adjust the stack column spans (image column) or the image's side.

## /about at 1440px — 31/100

Checks passed: 81% · screenshots 63% alike (two unrelated pages compare at about 55%).

Original: https://www.katieteague.com/about/  
Imported: /about (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Body font | Open Sans | Open Sans | same |
| Body text size | 17.7px | 17.7px | same |
| Lead text size | 29.8px | 29.7px | same |
| Label font | freight-sans-pro | Mukta (close stand-in) | close (85%) |
| Buttons size | 21.2px | 21.2px | same |
| Buttons letter spacing and case | 0.02em, none | 0.02em, none | same |
| Navigation size | 14.3px | 14.3px | same |
| Navigation letter spacing and case | 0.01em, none | 0.01em, none | same |
| Site title size | 14.3px | 14.3px | same |
| Site title letter spacing and case | 0.01em, none | 0.01em, none | same |
| Content width | 330px | 334px | same |
| Button corners | 6.4px | 8px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | KATIE TEAGUE, Visual Storyteller & Threshold Guide | 59 | Heading: freight-sans-pro 26.4px → Mukta 23.5px; Text color: #000000 → #202020; Italic lines: 1 → 0; Image placement: right, 43% wide → left, 31% wide; Image crop: 1.31:1 → 1.56:1; Height: 3064px → 774px |

What would close the gap:

- Site Styles → choices.typography.label = { family: "freight-sans-pro" } (Google Fonts), or upload it in Site Styles → Your fonts.
- Set the closing/pull line in italics (lead style).
- Adjust the stack column spans (image column) or the image's side.
- Use the original's image proportions (the block's aspect ratio).

## /about at 390px — 15/100

Checks passed: 28% · screenshots 85% alike (two unrelated pages compare at about 65%).

Original: https://www.katieteague.com/about/  
Imported: /about (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Body font | Josefin Sans | Open Sans | **differs** |
| Body text size | 24.6px | 17.1px | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | KATIE TEAGUE, Visual Storyteller & Threshold Guide | 38 | Heading: freight-sans-pro 22.5px → Mukta 19.6px; Text: Josefin Sans 24.6px italic → Open Sans 17.1px; Text color: #ffffff → #202020; Italic lines: 1 → 0; Image crop: 1.28:1 → 1.55:1; Height: 3857px → 1781px |

What would close the gap:

- Site Styles → choices.typography.body = { family: "Josefin Sans" } (Google Fonts), or upload it in Site Styles → Your fonts.
- choices.typography.scale.body.sizeMobile = 25
- Set the closing/pull line in italics (lead style).
- Use the original's image proportions (the block's aspect ratio).

## /conflict-as-threshold at 1440px — 34/100

Checks passed: 68% · screenshots 67% alike (two unrelated pages compare at about 55%).

Original: https://www.katieteague.com/conflict-as-threshold/  
Imported: /conflict-as-threshold (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Body font | Open Sans | Open Sans | same |
| Body text size | 14.3px | 14px | same |
| Lead text size | 29.8px | 29.7px | same |
| Label font | freight-sans-pro | Mukta (close stand-in) | close (85%) |
| Buttons size | 21.2px | 21.2px | same |
| Buttons letter spacing and case | 0.02em, none | 0.02em, none | same |
| Navigation size | 14.3px | 14.3px | same |
| Navigation letter spacing and case | 0.01em, none | 0.01em, none | same |
| Site title size | 14.3px | 14.3px | same |
| Site title letter spacing and case | 0.01em, none | 0.01em, none | same |
| Content width | 950px | 568px | **differs** |
| Button corners | 6.4px | 8px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Conflict as Rite of Passage | 25 | Background: #ffffff → #131313; Heading: freight-sans-pro 40.2px → Mukta 29.7px; Italic lines: 2 → 0; Height: 2159px → 810px |

What would close the gap:

- Site Styles → choices.typography.label = { family: "freight-sans-pro" } (Google Fonts), or upload it in Site Styles → Your fonts.
- choices.layout.contentWidth = 950
- Give the section its own background color (style.background = { type: "color", color: "#ffffff" }).
- Set the closing/pull line in italics (lead style).

## /conflict-as-threshold at 390px — 42/100

Checks passed: 57% · screenshots 83% alike (two unrelated pages compare at about 65%).

Original: https://www.katieteague.com/conflict-as-threshold/  
Imported: /conflict-as-threshold (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Body font | Open Sans | Open Sans | same |
| Body text size | 14.9px | 14px | same |
| Lead text size | 24.6px | 23.5px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Conflict as Rite of Passage | 25 | Background: #ffffff → #131313; Heading: freight-sans-pro 31.1px → Mukta 23.5px; Italic lines: 2 → 0; Height: 2452px → 630px |

What would close the gap:

- Give the section its own background color (style.background = { type: "color", color: "#ffffff" }).
- Set the closing/pull line in italics (lead style).

## /donate at 1440px — 38/100

Checks passed: 81% · screenshots 67% alike (two unrelated pages compare at about 55%).

Original: https://www.katieteague.com/donate/  
Imported: /donate (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 2: present | freight-sans-pro 45.4px | not found | **differs** |
| Body font | Open Sans | Open Sans | same |
| Body text size | 17.7px | 17.7px | same |
| Label font | freight-sans-pro | Mukta (close stand-in) | close (85%) |
| Buttons size | 21.2px | 21.2px | same |
| Buttons letter spacing and case | 0.02em, none | 0.02em, none | same |
| Navigation size | 14.3px | 14.3px | same |
| Navigation letter spacing and case | 0.01em, none | 0.01em, none | same |
| Site title size | 14.3px | 14.3px | same |
| Site title letter spacing and case | 0.01em, none | 0.01em, none | same |
| Content width | 1354px | 720px | **differs** |
| Section padding | 253px | 120px | **differs** |
| Button corners | 6.4px | 8px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Make a Difference | 88 | Heading: freight-sans-pro 45.4px → Mukta 45.4px; Height: 791px → 543px |

What would close the gap:

- Site Styles → choices.typography.label = { family: "freight-sans-pro" } (Google Fonts), or upload it in Site Styles → Your fonts.
- choices.layout.contentWidth = 1354
- choices.layout.sectionPadding = 253

## /donate at 390px — 55/100

Checks passed: 83% · screenshots 82% alike (two unrelated pages compare at about 65%).

Original: https://www.katieteague.com/donate/  
Imported: /donate (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 2: present | freight-sans-pro 34.4px | not found | **differs** |
| Body font | Open Sans | Open Sans | same |
| Body text size | 17.1px | 17.1px | same |
| Buttons: present | freight-sans-pro 19.2px | not found | **differs** |
| Section padding | 160px | 66px | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Make a Difference | 97 | Heading: freight-sans-pro 34.4px → Mukta 34.7px |

What would close the gap:

- choices.layout.sectionPaddingMobile = 160

## /education-for-teachers at 1440px — 38/100

Checks passed: 85% · screenshots 66% alike (two unrelated pages compare at about 55%).

Original: https://www.katieteague.com/education-for-teachers/  
Imported: /education-for-teachers (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Label font | freight-sans-pro | Mukta (close stand-in) | close (85%) |
| Buttons size | 21.2px | 21.2px | same |
| Buttons letter spacing and case | 0.02em, none | 0.02em, none | same |
| Navigation size | 14.3px | 14.3px | same |
| Navigation letter spacing and case | 0.01em, none | 0.01em, none | same |
| Site title size | 14.3px | 14.3px | same |
| Site title letter spacing and case | 0.01em, none | 0.01em, none | same |
| Button corners | 6.4px | 8px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | (no heading) | 67 | Image placement: center, 94% wide → none; Height: 1665px → 905px |

What would close the gap:

- Site Styles → choices.typography.label = { family: "freight-sans-pro" } (Google Fonts), or upload it in Site Styles → Your fonts.
- Adjust the stack column spans (image column) or the image's side.

## /education-for-teachers at 390px — 45/100

Checks passed: 67% · screenshots 80% alike (two unrelated pages compare at about 65%).

Original: https://www.katieteague.com/education-for-teachers/  
Imported: /education-for-teachers (local preview)

| Check | Original | Imported | |
|---|---|---|---|

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | (no heading) | 67 | Image placement: center, 94% wide → none; Height: 2135px → 1141px |

What would close the gap:

- Adjust the stack column spans (image column) or the image's side.

## /films at 1440px — 31/100

Checks passed: 72% · screenshots 64% alike (two unrelated pages compare at about 55%).

Original: https://www.katieteague.com/films/  
Imported: /films (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Body font | Open Sans | Open Sans | same |
| Body text size | 17.7px | 14px | **differs** |
| Label font | freight-sans-pro | Mukta (close stand-in) | close (85%) |
| Buttons size | 21.2px | 21.2px | same |
| Buttons letter spacing and case | 0.02em, none | 0.02em, none | same |
| Navigation size | 14.3px | 14.3px | same |
| Navigation letter spacing and case | 0.01em, none | 0.01em, none | same |
| Site title size | 14.3px | 14.3px | same |
| Site title letter spacing and case | 0.01em, none | 0.01em, none | same |
| Button corners | 6.4px | 8px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | (no heading) | 50 | Text: Open Sans 17.7px → Open Sans 14px; Text color: #000000 → #636363; Height: 2303px → 1575px |

What would close the gap:

- choices.typography.scale.body.size = 18
- Site Styles → choices.typography.label = { family: "freight-sans-pro" } (Google Fonts), or upload it in Site Styles → Your fonts.

## /films at 390px — 32/100

Checks passed: 54% · screenshots 76% alike (two unrelated pages compare at about 65%).

Original: https://www.katieteague.com/films/  
Imported: /films (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Body font | Open Sans | Open Sans | same |
| Body text size | 17.1px | 14px | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | (no heading) | 50 | Text: Open Sans 17.1px → Open Sans 14px; Text color: #000000 → #636363; Height: 1251px → 415px |

What would close the gap:

- choices.typography.scale.body.sizeMobile = 17

