# gett-failed-oreder-analysis

An analysis for ride failures via cancellation patterns and geospatial hex clustering


## Overview
Exploratory data analysis of 10,716 failed ride orders on the Gett 
platform, investigating cancellation patterns, timing, and geographic 
distribution.

## Key Findings
- 42% of failures occur before driver assignment — matching speed is 
  the primary bottleneck
- Failures peak at 8am and 21-23:00 during demand spikes
- Just 23 of 144 geographic hexagons account for 80% of all failures
- Customers wait 40-90 seconds longer when a driver is assigned

## Tools Used
Python, Pandas, Matplotlib, Seaborn, H3, Folium

## Files
- `gett_failed_orders.ipynb` — full analysis notebook
- `hex_map.html` — interactive geographic visualization
- `data/` — raw datasets