# BRM - GR 7 starter

A mobile-first, TikTok-inspired research prototype.

## Run locally
Open `index.html` in a modern browser.

## Included in this prototype
- Welcome screen and participant ID
- Random 50/50 assignment to Hedonic or Utilitarian placeholder condition
- Short-form feed-style opening-hook screen (8-second prototype timer)
- Draft 3-item curiosity questionnaire (NOT a validated scale)
- Voluntary continuation choice and visible viewing timer
- CSV export for a single browser session

## Important before real data collection
This is a UI/flow prototype, not a production research platform:
- Replace all visual placeholders with approved stimulus videos.
- Confirm the exact experimental conditions, hook exposure duration, questionnaire wording, and viewing protocol.
- The draft curiosity items are placeholders and must be replaced with the approved validated/adapted scale.
- Data is not sent to a central database. CSV export is local to the participant's browser.
- Browser-side random assignment is not suitable for controlled multi-participant allocation. Use a server/database-backed randomizer before launching the study.
- Add consent, privacy notice, secure data storage, and a researcher/admin export workflow before collecting real participant data.
