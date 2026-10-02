# Club Manager MVP

Mobile-first football management prototype inspired by the fast management loop of classic PC football managers.

## MVP 0.1.1
- 20 fictional clubs
- 440 generated players
- 38-matchday league
- Squad and starting XI management
- Deterministic match simulation
- League table
- Transfer market
- Club budget
- Stadium upgrade
- Local save in the browser
- Mobile-first UI for iPhone/Safari

## Deploy
Static, dependency-free site. No build command is required.

Vercel can serve the repository root directly.

## Current architecture
This first playable build is intentionally self-contained in `index.html` to make iteration and mobile testing frictionless. The simulation engine will be split from the UI once the gameplay loop is validated.
