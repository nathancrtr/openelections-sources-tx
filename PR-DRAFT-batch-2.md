# PR draft, batch 2 (sources): 2024 general sources for Clay, Erath, Haskell

(Not opened. Text for the owner to use or edit. Companion to the data-repo
PR adding the three county CSVs.)

## Title

2024 general: add Clay, Erath and Haskell sources, batch 2 search log

## Body

Adds the source files behind the Clay, Erath and Haskell 2024 general
precinct files:

- `2024 Clay County, TX precinct-level results.xml`: Clarity ENR precinct
  detail export (`detail.xml` from `detailxml.zip`, version 353790).
- `2024 Erath County, TX precinct-level results.xlsx`: the county's cast
  vote record export, one row per ballot, with a Precinct column. The county
  did not post a precinct results report for this election.
- `2024 Haskell County, TX precinct-level results.pdf`: scanned
  spreadsheet "GENERAL ELECTION BBM, EV & ED 11/5/2024", 17 pages, image
  only, with mail, early and election-day sections by precinct.

Also adds `2024/general/SOURCES-2024-found.md`: for each of the 25 unchecked
counties from Bailey to Irion, the URL, fetch date, SHA-256 and document type
of what was found, or the closest county-wide document and the clerk or
elections administrator a records request would go to. 22 of the 25 have
nothing precinct-level online. It also records that no public SOS download of
the §67.017 precinct-by-precinct filings for November 2024 could be found.

## Unsure of

- Whether the project wants the search log file in the repo or only in the
  PR text; it is easy to drop from the PR.
- Erath's CVR is 5.4 MB and contains ~490 small embedded images (likely
  write-in captures); it is the county's own export, unmodified.
