# Calendrier fantôme · Instagram

Prototype: competitor Instagram posts read through Meta's official Business Discovery API (no scraping), turned into posting rhythm, formats, hashtags and a "ghost calendar" of their probable posts next week.

- Competitors arrive pre-filled from Agorapulse (`?c=Brand A,Brand B`), their Instagram handles are deduced and only need a one-click confirmation.
- Demo mode uses fictional brands only.
- The Meta access token is pasted at runtime, kept in `sessionStorage` for the tab, sent only to `graph.facebook.com`. Nothing secret lives in this repo.
