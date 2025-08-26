# FootballTeamSelectionWebApp

Simple static front-end that reads `team_data.csv` and shows a dropdown of NFL teams. Selecting a team displays the team name, division, and logo.

How to run

Open `index.html` in a browser. If you're serving files from a local server, the page will try to fetch `team_data.csv` from the same folder; otherwise it uses an embedded fallback copy.

Quick server (Python 3):

```bash
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

Notes

- No frameworks used. All code is in `index.html`.
- Team data is read from `team_data.csv`. If fetch is not possible (file://), the page will use a built-in fallback.

Files added

- `index.html` — single-file HTML/CSS/JS app that implements the dropdown and team card.
