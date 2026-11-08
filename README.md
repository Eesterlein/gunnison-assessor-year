# The Assessor's Year — Gunnison County, Colorado

An unofficial, interactive guide to the property assessment cycle in Gunnison County, Colorado.

**Live site:** https://eesterlein.github.io/gunnison-assessor-year/

## What it shows

- **Which year your bill pays for.** Pick the year you pay, and the page explains the chain: home sales → price day (June 30) → count day (January 1) → tax year → payment.
- **How the years overlap.** A chart of five tax years side by side, showing why several cycles run at once.
- **The full assessor calendar** for 2026 and 2027 under Colorado's alternate protest and appeal procedure: notices, protests, CBOE hearings, certifications, abstract, state reports, audit, levies and tax payments.
- **Coming up.** A countdown to the next deadlines, based on the dates in the calendar.

## Updating dates

All calendar dates live in the `EV` array in `index.html`. Each event has a `dates` entry per year (`{2027:["2027-05-01"]}` for one day, or `[start, end]` for a window). Add a new year's dates there and add the year to `YEARS`; the "Coming up" box picks them up automatically.

## Sources

- Colorado Division of Property Taxation, 2026 Assessors' Year Calendar
- Gunnison County 2027 property owner timeline handouts (SB26-046 deadlines)
- Colorado Revised Statutes, Title 39

## Disclaimer

This is an independent, personal project. It is not produced or endorsed by Gunnison County or the Gunnison County Assessor's Office. Dates can change; for official deadlines, contact the Assessor's Office or visit gunnisoncounty.org.
