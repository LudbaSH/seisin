# Changelog

All notable changes to Seisin are documented here. This project follows
[Semantic Versioning](https://semver.org/).

## v1.0.0 - 2026-07-16

First public release. Windows only. Seisin is a free desktop app that keeps an
entire job search in one place, every application, interview and offer, and turns
the record into analytics automatically.

### Highlights
- Application tracking with a full status pipeline, from planned to offer
- Analytics: weekly pace, pipeline health, response by source, average response
  time, and a conversion funnel, each with a plain-English explanation
- Interview suite with rounds, contacts, research notes, and a prep checklist
- Offer comparison side by side, with currency conversion for roles abroad
- Resume storage with tagging, linked to the applications each version was used for
- Interactive world map of where you are applying
- Add roles by hand, paste a job URL to parse the posting, or import from CSV or
  Excel with column mapping; export to CSV, Excel, or JSON
- Light, dark, and midnight themes with a custom accent colour
- Privacy mode that blurs salary figures and names

### Your data
- Everything is stored in a SQLite file on your own machine. There is no account
  and no sign-in.
- Seisin makes three network requests. None of them carry your data, and every one
  can be avoided: the update check on launch, which you can switch off in Settings
  under About; job-URL autofill, only when you paste a link; and the exchange-rate
  refresh, only when you ask for it.
