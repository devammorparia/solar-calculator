# Solar Calculator

## Project goal
A Java app that estimates how much of a household's electricity could be
covered by solar panels, and how much CO₂ that would avoid, using NREL's
PVWatts API.

## MVP scope
- Enter location, system size, and monthly electricity usage
- Fetch monthly solar production from the PVWatts API
- Show monthly coverage and annual CO₂ avoided in a command-line summary
- Unit tests for the calculations

## Future plans
- JavaFX window with an input form
- Bar chart of monthly production vs. usage
- Compare several system sizes (e.g., 3, 6, 9 kW) in one chart
- Cache API responses in a local JSON file so the app works offline
- Simple tree-shading adjustment (shade-level dropdown)

## Tech stack
- Java 17+, Maven
- Gson (JSON parsing), JavaFX (charts), JUnit 5 (tests)
- NREL PVWatts v8 API, EPA eGRID emissions data
- Git and GitHub

## System diagram
![System diagram](docs/system-diagram.png)
## Eisenhower matrix
[View the Eisenhower matrix](docs/eisenhower-matrix.pdf)
