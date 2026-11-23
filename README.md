# Theatrical Release Calendar

Rolling 3-4 month US theatrical release calendar, cross-checked across:
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
