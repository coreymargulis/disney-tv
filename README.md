# Disney World wait board for a TV

A single page that shows live Walt Disney World wait times, rotating through Magic Kingdom, EPCOT, Hollywood Studios and Animal Kingdom. Made to run fullscreen on a TV, tablet or spare screen.

Data: [ThemeParks.wiki](https://themeparks.wiki) free API, refreshed every 3 minutes. If the data can't load, the page says so and shows no times.

## Link options

- `?trip=2027-02-13` shows a countdown to that date (remembered on that screen).
- `?label=Disney%20World` changes the countdown text.
- `?park=mk` (or `ep`, `hs`, `ak`) pins one park; `?rotate=0` stops rotating.
- `?dwell=30` seconds per park (default 20).

Remote or keyboard: left/right switches parks, Enter pauses rotation. Tap anywhere for full screen.
