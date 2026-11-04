# 2024 general election precinct sources: unified log for the 70 counties left open on #458

Three sessions searched on 2026-11-04. This file is the index; the per-batch
logs hold the full entries (URL, fetch date, SHA-256, document type, official
status, and for every county without a file the closest online document and
the office a records request goes to):

- `SOURCES-2024-found-batch-1.md`: the ten counties that already had a file
  here (Cochran, Hill, McMullen, Newton, Rains, Terrell, Webb, Wichita,
  Wilson, Yoakum); problems found with the Rains, Cochran, Webb and McMullen
  files.
- `SOURCES-2024-found-batch-2.md`: Bailey through Irion (25 counties), and
  the statewide SOS filing search.
- `SOURCES-2024-found-batch-3.md`: Jackson through Zapata (35 counties).

## Statewide SOS filing (Election Code 67.017)

Not online. Both source-hunt sessions, independently and within their time
box, found that the SOS precinct-by-precinct page returns the SOS not-found
page to every kind of fetch, that no public download of the November 2024
county filings exists, and that the 2022 file names in this repo look like
an export from the filing system rather than a public page. The one-request
alternative is a public-information request to the SOS Elections Division:
elections@sos.texas.gov, 512-463-5650, P.O. Box 12060, Austin, TX
78711-2060. Owner's call.

## Files added in this round (4)

| county | file | kind | official? |
|---|---|---|---|
| Clay | `2024 Clay County, TX precinct-level results.xml` | Clarity ENR precinct detail XML (zip from results.enr.clarityelections.com, version 353790) | unlabelled, dated before canvass; totals match TLC |
| Erath | `2024 Erath County, TX precinct-level results.xlsx` | cast vote record, one row per ballot, 18,441 ballots (county Archive Center) | unlabelled; totals match TLC |
| Haskell | `2024 Haskell County, TX precinct-level results.pdf` | scanned spreadsheet printout, 17 pages, mail / early / election day sections by precinct (county elections page) | unlabelled |
| Polk | `2024 Polk County, TX precinct-level results.pdf` (+ `... summary.pdf`) | commissioners court canvass packet with the ES&S Canvass Results Report, 73 pages, scanned (CivicClerk); unofficial cumulative report alongside | official |

## Existing files with problems (batch 1)

- Rains: the existing csv covers only Proposition A, a school trustee race
  and city races; it is not a general election report. The county posts
  cumulative reports only. Records request: Lisa Kneifl, Elections
  Administrator, 220 W Quitman St, Suite E, Emory, TX 75440, (903)
  473-5009, lisa.kneifl@rainscounty.gov.
- Cochran: the tally sheet's EV column includes mail ballots (totals run 5%
  above TLC). Cochran County Clerk, 100 N Main St, Morton, TX 79346, (806)
  266-5508, for an official precinct report.
- Webb: the file is an unofficial scan; the county agenda server that holds
  canvass packets refused connections from the session network.
- McMullen: the unlabelled election-day report was taken as Pct 3 by
  elimination.

## Counties with nothing precinct-level online (57)

Each name links to a full entry in the batch log named in the column.

| batch | counties |
|---|---|
| 1 | Rains |
| 2 | Bailey, Bee, Blanco, Briscoe, Castro, Childress, Crane, Crockett, Crosby, Culberson, Dallam, Deaf Smith, Dickens, Donley, Edwards, Fisher, Frio, Hansford, Hartley, Howard, Hudspeth, Irion |
| 3 | Jackson, Karnes, Kent, King, Kinney, Kleberg, Knox, Lavaca, Lipscomb, Loving, Marion, Mason, Maverick, Morris, Navarro, Pecos, Presidio, Real, Roberts, Runnels, Schleicher, Shackelford, Shelby, Sherman, Somervell, Sterling, Trinity, Upton, Uvalde, Wheeler, Wilbarger, Willacy, Young, Zapata |

Patterns worth knowing before writing the requests: most of these counties
post a county-wide cumulative or summary report and nothing else; at least
twelve (Bailey, Blanco, Briscoe, Culberson, Dickens, Edwards, Fisher, Frio,
Hudspeth, Irion, Karnes, Navarro, King) post precinct reports for other
elections, so the November 2024 report exists and was simply not posted;
Karnes says in writing that its precinct report is available in person
only; Somervell's site could not be reached from the session network and
may just need a retry.
