# GravityIQ — WNBA Basketball Analytics Dashboard

Interactive basketball analytics prototype created for the **WNBA Mini Data Jam powered by AWS**, organized with Girls Who Code.

## Overview
GravityIQ explores player gravity—how player positioning influences defensive attention—through an interactive, game-oriented scouting dashboard. The prototype helps turn basketball location and gravity measurements into visual stories that coaches and analysts can discuss.

## Features
- Interactive game, team and player selection controls.
- On-ball and off-ball, perimeter and interior gravity comparisons.
- Player/game gravity summaries and visual comparisons.
- Court visualization generated with Python and Matplotlib.

## Technology
- **Front end:** HTML, CSS and vanilla JavaScript; self-contained dashboard pages.
- **Court rendering:** Python, NumPy and Matplotlib (`wnba_court.py`).
- **Analysis inputs:** Event-provided game/player gravity tables and player/team lookup data, transformed into the demo dashboards.

## Getting started
1. Download or clone the repository.
2. Open `index.html` in a browser for the game overview dashboard.
3. Open `GravityIQ_WORKING.html` for the alternate scouting intelligence dashboard.
4. To regenerate a court image, install `matplotlib` and `numpy` and run `python wnba_court.py -o court.png`.

The HTML dashboards are self-contained and do not require a backend or API key.

## Data and attribution
The original ZIP included WNBA Mini Data Jam data tables and an event data dictionary. **Raw event-provided datasets and guide are intentionally not republished in this GitHub-ready package** until their redistribution permissions are confirmed. Some preprocessed/example values are embedded directly in the HTML demos. Confirm event data-sharing rules before making the repository public.

This is an independent student hackathon project, not an official WNBA analytics product and not affiliated with or endorsed by the WNBA, AWS, or Girls Who Code.


## Future improvements
- Separate data preprocessing from frontend views.
- Document calculation definitions for gravity metrics and chart axes.
- Add screenshots and walkthrough of scouting insights.
- Verify data licensing and add documented data loading if redistribution is permitted.
