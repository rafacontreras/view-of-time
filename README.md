# Jehovah's View of Time

A simple calculator based on 2 Peter 3:8. If 1,000 years is like 1 day with Jehovah, how old would you be on that scale?

Enter any age in human years. The page shows your age in days, hours, minutes and seconds, how much of one 24-hour day it fills, and totals in hours, minutes and seconds. It works in English and Spanish (use the toggle at the top right).

**Live page:** https://rafacontreras.github.io/view-of-time/

## The math

1 day = 24 hours = 1,440 minutes = 86,400 seconds.

Divide that by 1,000 years:

- 1 human year = 1.44 minutes
- 1 human year = 86.4 seconds

So your age Ã— 86.4 gives your age in seconds.

| Human age | Age on this scale |
|-----------|-------------------|
| 1 year    | 1 minute, 26.4 seconds |
| 25 years  | 36 minutes |
| 40 years  | 57 minutes, 36 seconds |
| 70 years  | 1 hour, 40 minutes, 48 seconds |
| 100 years | 2 hours, 24 minutes |
| 969 years | 23 hours, 15 minutes, 21.6 seconds |
| 1,000 years | 1 day |

Ages over 1,000 roll into full days. Results are calculated in tenths of a second so decimal ages stay accurate.

## Files

- `index.html`: the whole app. It has no server, database or build step.
- `README.md`: this file.

The page loads two fonts (Fraunces and Source Sans 3) from Google Fonts. If they can't load, it falls back to standard fonts and still works.

## Changing it

- Text for both languages is in the `I18N` section near the bottom of `index.html`. To change a word or add a language, edit that section.
- Colors and fonts are the variables at the top of the `<style>` block. There is a light and a dark version.

## Hosting

This repo is published with GitHub Pages. In **Settings â†’ Pages**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**.
