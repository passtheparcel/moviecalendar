# Theatrical Release Calendar

Rolling 3-4 month US theatrical release calendar, cross-checked across
(window currently Nov 25, 2026–Apr 2027; Thanksgiving week added Nov 23,
2026 and April added Nov 24, 2026 — the file name still says 2026-12, but
the rows start Nov 25):
- The Numbers release schedule (base: distributor + Wide / Limited)
- FirstShowing.net release schedules (curated cross-check)
- IMDb US calendar (for IMDb IDs)

Scope: wide-only, plus notable limited from major / mini-major distributors
(A24, Neon, Searchlight, Focus, Sony Pictures Classics, Bleecker Street,
IFC, Black Bear, Briarcliff, Lionsgate, MUBI, GKIDS, Netflix, Roadside, etc).
Wide expansions are ignored for now. Re-releases are excluded for now —
see `re-releases-excluded-for-now.csv`.

`MajorDistributor` is Y for studio and major mini-major distributors
(Disney, Warner Bros., Universal, Paramount, Sony, 20th Century, Amazon MGM,
Lionsgate, A24, Neon, Searchlight, Focus, Sony Pictures Classics, Bleecker
Street, IFC, Black Bear, Briarcliff, MUBI, GKIDS, Netflix, Roadside, Angel
Studios) and N for smaller / niche distributors (e.g. Vertical Entertainment,
Magenta Light Studios, Cineverse, Ketchup, Viva Pictures, Prathyangira).

For any title where sources disagree, the date in this file is the
adjudicated date, with the reasoning in the Notes column.

`TicketsOnSale` is a YYYY-MM-DD date when a ticket-sale date is known for
a title (from the user's Patreon ticket-sale emails, matched by title),
blank otherwise. Known so far: Jumanji: Open World Nov 30, 2026; The Angry
Birds Movie 3 Dec 3, 2026; The Beekeeper 2 Dec 18, 2026.

`PreviewDate` is the day before `ReleaseDate` (YYYY-MM-DD) for every row —
previews typically run the evening before a release. It is derived from the
release date, not sourced per film, so a film with earlier fan previews or
a different preview pattern may differ.

`TrackDates` is a comma-delimited list of YYYY-MM-DD dates to track for a
title. For a Friday release it is Thursday (preview) + Friday (release),
e.g. "2026-12-24, 2026-12-25". For a non-Friday release it is left blank
until the user decides what dates to track — those titles are flagged in
Notes as "Non-Friday release - tracking dates to be decided".

## Files

- `master-calendar-2026-12-2027-03.csv` — the master list, sorted by date
- `master-calendar-2026-12-2027-03.json` — same data as JSON, with metadata
- `re-releases-excluded-for-now.csv` — re-releases held out for now

## Pull it

CSV:
```
https://raw.githubusercontent.com/passtheparcel/moviecalendar/main/master-calendar-2026-12-2027-03.csv
```

JSON:
```
https://raw.githubusercontent.com/passtheparcel/moviecalendar/main/master-calendar-2026-12-2027-03.json
```

No auth needed — the repo is public.

## Refresh

Refreshed weekly (planned). Each refresh updates the CSV + JSON in place,
so the URLs above always return the latest version.
