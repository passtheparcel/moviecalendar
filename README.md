# Theatrical Release Calendar

Rolling 3-4 month US theatrical release calendar, cross-checked across:
- a Patreon calendar image (2026 only)
- The Numbers release schedule
- IMDb US calendar

Scope: wide-only, plus notable limited from major / mini-major distributors
(A24, Neon, Searchlight, Focus, Sony Pictures Classics, Bleecker Street,
IFC, Black Bear, Briarcliff, Lionsgate, MUBI, GKIDS, Netflix, Roadside, etc).
Wide expansions are ignored for now. Re-releases are excluded for now —
see `re-releases-excluded-for-now.csv`.

For any title where sources disagree, the date in this file is the
adjudicated date, with the reasoning in the Notes column.

## Files

- `master-calendar-2026-12-2027-03.csv` — the master list, sorted by date
- `master-calendar-2026-12-2027-03.json` — same data as JSON, with metadata
- `re-releases-excluded-for-now.csv` — re-releases held out for now

## Pull it

CSV:
```
https://raw.githubusercontent.com/<user>/<repo>/main/master-calendar-2026-12-2027-03.csv
```

JSON:
```
https://raw.githubusercontent.com/<user>/<repo>/main/master-calendar-2026-12-2027-03.json
```

Replace `<user>` / `<repo>` with this repo's owner and name.
No auth needed if the repo is public.

## Refresh

Refreshed weekly (planned). Each refresh updates the CSV + JSON in place,
so the URLs above always return the latest version.
