# Sources found for 2024 general precinct results, batch 2 (Bailey through Irion)

Searched 2026-11-04. Scope: the 25 unchecked counties from Bailey to Irion on
issue openelections/openelections-data-tx#458 that had no file under
`2024/general/`. Each county's own site (many on `newtools.cira.state.tx.us`),
its elections administrator or clerk page, and its commissioners court agenda
or minutes system were checked, plus web search. "Precinct-level" means votes
by precinct for the November 5, 2024 general election. A county-wide
cumulative report, canvass form or reconciliation form alone does not count.

## Statewide SOS filing (Election Code §67.017)

No public download of the county precinct-by-precinct filings for November
2024 was found. `https://www.sos.state.tx.us/elections/laws/precinct-by-precinct-report.shtml`
returns the SOS "requested file was not found" page (HTTP 403) even with a
browser user agent, on both `sos.state.tx.us` and `sos.texas.gov`; the
Wayback Machine has a 2024-02-28 capture of it but `web.archive.org` is not
reachable from this environment. Guessed successors
(`precinct-by-precinct-returns-2024.shtml`, `-2022`, `-nov2024`, and the
2014 page that search engines still index) all return the same not-found page.
The SOS forms index lists "Precinct-by-Precinct Returns" only as a filing
requirement. The 2022 file names in this repo
(`<COUNTY>_COUNTY-2022_NOVEMBER_8TH_GENERAL_ELECTION_1182022-<original name>`)
look like an export from the SOS filing system rather than a public page, so
the 2024 equivalent probably needs a records request to the SOS Elections
Division (elections@sos.texas.gov, 512-463-5650, P.O. Box 12060, Austin, TX
78711-2060) rather than a URL. The SOS "November 2024 Voter Registration
Figures" page (`https://www.sos.state.tx.us/elections/historical/nov2024.shtml`)
does give each county's precinct count, used below as a sanity check.

## Found (3)

### Clay
- File: `2024 Clay County, TX precinct-level results.xml`
- URL: `https://results.enr.clarityelections.com/TX/Clay/122307/353790/reports/detailxml.zip` (version 353790, the current version per `.../122307/current_ver.txt`); linked from `https://www.claycountytx.net/electionsadmin` ("General Election November, 05, 2024")
- Fetched: 2026-11-04
- SHA-256 (detail.xml, as saved): `8c11c9d0c9a8686aafc3691fc74d2dba356e4a7f14d539dccbaf70bdf3fe9518`; of the zip as downloaded: `8852ab554f4add2cd049d8b75b07012448ac21a3ba1fdcb5accefe0fe89bfd50`
- Document: Clarity (Scytl) election-night-reporting precinct detail XML, 28 contests, 16 precincts, vote types Absentee / Early / Election Day / Provisional, timestamp 11/8/2024 9:30 AM
- Official status: the export carries no label. It is dated three days after the election and before the canvass; treat as unofficial unless the county confirms it is the canvassed data. SOS lists 17 precincts for Clay; the export and TLC's VTD file both have 16.

### Erath
- File: `2024 Erath County, TX precinct-level results.xlsx`
- URL: `https://www.co.erath.tx.us/ArchiveCenter/ViewFile/Item/1703` (Archive Center > Elections, "2024-11 Cast Voter Records General Election"; `co.erath.tx.us` sits behind Cloudflare and refused scripted fetches, the same file was fetched from the alias `https://tx-erathcounty.civicplus.com/ArchiveCenter/ViewFile/Item/1703`)
- Fetched: 2026-11-04
- SHA-256: `9b876416118818bddb40ca5e70f784091dc7809eb99ada2bef9c30dd7b0bcf2c`
- Document: cast vote record export (one row per ballot, 18,441 ballots, 21 precincts, one column per contest, ES&S style labels such as "REP Donald J. Trump/JD Vance (1)", "undervote", "overvote"). Not a results report; precinct totals are computed by counting rows. No vote-method column.
- Official status: not labelled. The county posted it as the record of the canvassed election; its candidate totals match the TLC VTD data exactly. SOS lists 22 precincts; the CVR and TLC both have 21.

### Haskell
- File: `2024 Haskell County, TX precinct-level results.pdf`
- URL: `https://www.haskellcountytx.gov/upload/page/7706/precinct%20by%20precinct%20for%20nov%202024%20election.pdf`, linked from `https://www.haskellcountytx.gov/page/haskell.Elections`
- Fetched: 2026-11-04
- SHA-256: `f2f55f63755248b3ef0f4e4a8892366f0b751b4d2d0c1365a47fb05f04ab5743`
- Document: scanned spreadsheet printout "GENERAL ELECTION BBM, EV & ED 11/5/2024", 17 pages, image only (no text layer). Pages 1 to 3: combined grid with 10 election-day precinct columns plus BBM, EV and TOTAL. Pages 4 to 6: ballots by mail by precinct. Pages 8 to 10: early voting by precinct. Pages 11 to 13: election day by precinct. Pages 14 to 17: BBM/EV totals. Page 7 blank.
- Official status: not labelled on the document or the page. SOS lists 11 precincts for Haskell; the sheet has 10.

## Not found (22)

Each entry gives the closest document that is online, and the office a
records request would go to. Contacts come from the county's own pages
unless the SOS county election officials directory
(`https://www.sos.state.tx.us/elections/voter/county.shtml`) is named.

### Bailey — not found
- Closest: `https://newtools.cira.state.tx.us/upload/page/8143/2024/Bailey%20County%20Official%20Results%20Nov%205%202024.pdf` (ES&S Electionware Summary Results Report, scanned, 3 pp, "OFFICIAL RESULTS", county totals with Absentee/Early/Election Day). Landing page `https://newtools.cira.state.tx.us/page/bailey.Elections`. The same page has precinct results for the March 2024 primary, so the county can produce them.
- Records request: Irene Espinosa, County Clerk, Bailey County Courthouse, 300 S. 1st Street, Suite 200, Muleshoe, TX 79347; (806) 272-3044; iespinosa@co.bailey.tx.us (from `https://newtools.cira.state.tx.us/page/bailey.Elections`).

### Bee — not found
- Closest: `https://www.beecounty.texas.gov/DocumentCenter/View/411/November-5-2024-General-Election-PDF` (Hart Verity cumulative report, "Official Results", 11 pp incl. the SOS reconciliation form, county totals with Absentee/Early/Election Day). Landing page `https://www.beecounty.texas.gov/216/Elections-History`. Nov 14, 2024 canvass minutes and agenda packet on `beecountytx.iqm2.com` have no returns attached.
- Records request: Laura Warnix, Elections Administrator, Bee County, PO Drawer B, Beeville, TX 78104 (1511 E Toledo St., Beeville, TX 78102); 361-621-1519; elections@beecounty.texas.gov (from `https://www.beecounty.texas.gov/162/Elections-Administration`).

### Blanco — not found
- Closest: `https://newtools.cira.state.tx.us/upload/page/4006/2024%20Elections/Gen%20Election/Official%20Canvass.pdf` (SOS Canvass Report, signed 11-18-2024, scanned, 25 pp, county totals) and `.../ENR%20Unofficial%20Results%2011.05.24.pdf` (SOS unofficial results report, 6 pp, county totals by method). Landing page `https://newtools.cira.state.tx.us/page/blanco.Elections`. The county's results page posts "Precinct by Precinct" reports for 2020 to 2022 but none for Nov 2024.
- Records request: Rosemary Adame, Elections Administrator, Blanco County, P O Box 13, Johnson City, TX 78636 (101 East Cypress Street, Suite 109); 830-868-7168; public information requests to piarequest@co.blanco.tx.us (from `https://newtools.cira.state.tx.us/page/blanco.Elections`).

### Briscoe — not found
- The elections page (`https://newtools.cira.state.tx.us/page/briscoe.Elections`) lists "Unofficial Results" and "CVR" for Nov 5, 2024, but both links (`.../upload/page/5196/11.05.2024.pdf` and `.../November%205.%202024%20General%20Election.CVR.xlsx`) return 404. The county posts precinct results for other elections.
- Records request: Amy Fuston, County Clerk, Briscoe County, PO Box 555 (415 Main St.), Silverton, TX 79257; 806-823-2131 ext. 2; coclerk@co.briscoe.tx.us (from the elections page).

### Castro — not found
- Elections page (`https://newtools.cira.state.tx.us/page/castro.Elections`) holds only 2025 and 2026 items. Commissioners court minutes are on an external server (`http://104.245.77.180:8082`) that was unreachable.
- Records request: Teresa Sims, Elections Administrator, Castro County, 100 E Bedford St., Rm 113, Dimmitt, TX 79027; 806-647-2080; tsims@castrocounty.org (from `https://newtools.cira.state.tx.us/page/castro.ElectionsAdministrator`).

### Childress — not found
- Closest: Nov 18, 2024 commissioners court special-meeting minutes with the SOS "Canvass Results Entry" attached (`https://www.childresstx.us/pages/commissioner-court-minutes`, item "Special Meeting- November 18th, 2024"; scanned, 5 pp, county totals by method). Childress runs a single countywide vote center. The county posted a precinct-category xlsx for Nov 2026, so the same export for Nov 2024 is plausible on request.
- Records request: Jennifer Jones, Elections Administrator, Childress County, Courthouse, Box 13, Childress, TX 79201 (100 Ave E NW, STE 13); (940) 937-6144; elections@childresstx.us (from the SOS county directory).

### Crane — not found
- Closest: `https://newtools.cira.state.tx.us/upload/page/1153/Summary%20Results%20Report.pdf` (ES&S Electionware summary, "UNOFFICIAL RESULTS", election night 8:32 PM, 4 pp, county totals by method). Landing page `https://newtools.cira.state.tx.us/page/crane.Election.Results`. No canvass or reconciliation for Nov 2024 posted.
- Records request: Andrea Flores, District & County Clerk, Crane County, P.O. Box 578, Crane, TX 79731 (201 W. 6th St, Room 110); (432) 558-3581; coclerk@co.crane.tx.us (from the SOS county directory and `https://newtools.cira.state.tx.us/page/crane.County.Clerk`).

### Crockett — not found
- Closest: Nov 15, 2024 called-session minutes approving the canvass (`https://newtools.cira.state.tx.us/upload/page/9743/2024/111524.pdf`, 2 pp, scanned, no figures; "Exhibit A" referenced but not attached). Elections page has only 2026 documents.
- Records request: Ninfa Preddy, District & County Clerk, Crockett County, P.O. Drawer C, Ozona, TX 76943 (909 Avenue D); (325) 392-2022; ninfa.preddy@co.crockett.tx.us (from the SOS county directory and `https://newtools.cira.state.tx.us/page/crockett.CountyClerk`).

### Crosby — not found
- Elections page (`https://newtools.cira.state.tx.us/page/crosby.Elections`) has no Nov 2024 results of any kind (it has Nov 2022 and Nov 2026 cumulative reports). No minutes online.
- Records request: Tammy Kaye Marshall, County Clerk, Crosby County, 201 West Aspen, Ste. 102, Crosbyton, TX 79322; (806) 675-2334; countyclerk1@crosbycountytx.com (from the SOS county directory and `https://newtools.cira.state.tx.us/page/crosby.County.Clerk`).

### Culberson — not found
- Closest: `https://www.co.culberson.tx.us/upload/page/0086/2024%20Election/11052024_imulative_results_report.pdf` (Hart Verity Cumulative Results Report, scanned, 11 pp, "Official Results", 4 of 4 precincts, county totals only). Landing page: `https://www.co.culberson.tx.us/page/Elections%202019-2025`. The county posted precinct reports for March 2022, so a Nov 2024 precinct report likely exists on request.
- Records request: Tina Urias, County Clerk, Culberson County, P.O. Box 158, Van Horn, TX 79855; 432-283-2058; tina.urias@co.culberson.tx.us (from `https://www.co.culberson.tx.us/page/County.Clerk`).

### Dallam — not found
- `http://www.dallam.org/vote/` links only the Nov 2026 local results; `/vote/110524results.pdf` and ~17 other guessed names 404. Wayback has a 2024-11-30 snapshot of that page (`http://web.archive.org/web/20241130120617/http://www.dallam.org/vote/`) that this session could not reach.
- Records request: Terri Banks, County & District Clerk, Dallam County, P.O. Box 1352, Dalhart, TX 79022; (806) 244-4751; clerk@dallam.org (from `http://www.dallam.org/county/clerk.shtml`).

### Deaf Smith — not found
- County Clerk page (`https://www.co.deaf-smith.tx.us/page/deafsmith.County.Clerk`) now posts only 2025–2026 cumulative reports; nothing from Nov 2024 remains. Wayback has a 2024-12-03 snapshot of `https://www.co.deaf-smith.tx.us/page/deafsmith.Elections` that this session could not reach.
- Records request: Rachel Garman, County Clerk / Elections Administrator, Deaf Smith County, 235 East 3rd Street, Room 203, Hereford, TX 79045; 806-363-7077; fax 806-363-7023; no email listed (from `https://www.co.deaf-smith.tx.us/page/deafsmith.Election.Administrator`).

### Dickens — not found
- Closest: `https://newtools.cira.state.tx.us/upload/page/1679/image4101.pdf` (Hart Verity Cumulative Results Report, scanned, 5 pp, "Official Results", 6 of 6 precincts, county totals only; landing page `https://www.co.dickens.tx.us/page/dickens.Elections`). Nov 12, 2024 commissioners court minutes record the canvass motion without figures. The county posted precinct reports for Nov 2025 and the 2025 runoff, so one for Nov 2024 likely exists on request.
- Records request: Danay Carnes, District & County Clerk, Dickens County, P.O. Box 120, Dickens, TX 79229; (806) 623-5531; danay.carnes@co.dickens.tx.us (from `https://www.co.dickens.tx.us/page/dickens.County.Clerk`).

### Donley — not found
- Closest: `https://www.co.donley.tx.us/upload/page/0109/Unofficial%20Results.pdf` (SOS "Election Unofficial Results Report" form, scanned, 5 pp, county totals only; landing page `https://www.co.donley.tx.us/page/Elections.Archive`). An "Election Day 2024.pdf" on the same page is election-day turnout by precinct (101, 201, 301, 303, 401), not votes. No Nov 2024 canvass minutes posted.
- Records request: Vicky Tunnell, County Clerk, Donley County, PO Drawer U, Clarendon, TX 79226; (806) 874-3436; doncoclerk@co.donley.tx.us. Open records page directs requests to "Donley County Clerk, Open Records Request, Drawer U, Clarendon, TX 79226, (806) 874-3625" (from `https://www.co.donley.tx.us/page/County.Clerk`).

### Edwards — not found
- Closest: `http://www.co.edwards.tx.us/upload/page/0104/Unofficial%20Results%20of%20General%20Election%202025.pdf` (despite the file name, this is the Nov 5, 2024 ES&S Electionware summary, "UNOFFICIAL RESULTS", scanned, 7 pp, county totals by method). Landing page `https://www.co.edwards.tx.us/page/Elections.Past`. The "Precinct 1" to "Precinct 4" links there are sample ballots. Nov 18, 2024 canvass minutes have no figures. The county posts precinct reports for 2025 and 2026.
- Records request: Olga Lydia Reyes, County and District Clerk / Elections Official, Edwards County, PO Box 184 (101 E. Main St.), Rocksprings, TX 78880; (830) 683-2235; clerk@swtexas.net (from `https://www.co.edwards.tx.us/page/Elections.Home`).

### Fisher — not found
- Closest: `https://www.fishercounty.org/upload/page/7798/docs/CountyClerk/Elections/2024/Official%20results.pdf` (ES&S Electionware summary, "Official Results", run 11/18/2024, image only, 8 pp, county totals by method). Landing page `https://www.fishercounty.org/page/fisher.ElectionPage`. Nov 18, 2024 canvass minutes include a 20-page SOS Canvass Report with county totals only. The "Box 1/4/10/12" links are sample ballots; the clerk did post box-by-box results for the March 2024 primary.
- Records request: Pat Thomson, County Clerk, Fisher County, P.O. Box 368 (112 N. Concho St.), Roby, TX 79543; (325) 776-2151; info@fishercounty.org; the county posts a PIA request form at `https://www.fishercounty.org/upload/page/7774/docs/TEXAS%20PIA%20REQUEST%20FORM.pdf` (from `https://www.fishercounty.org/page/fisher.County.Clerk`).

### Frio — not found
- Closest: `https://www.co.frio.tx.us/upload/page/0099/NewFolder/DOC111924-001.pdf` (SOS Canvass Report, signed 11/19/2024, scanned, 27 pp, county totals) and `.../DOC110824-001.pdf` (SOS unofficial results report, 7 pp, county totals by method). Landing page `https://www.co.frio.tx.us/page/elect.home`. The county posted a precinct-by-precinct report for Nov 2022, so one for 2024 should exist.
- Records request: Daniella Perez, Elections Administrator, Frio County, 500 E. San Antonio St., Box 5, Pearsall, TX 78061-3145 (office 650 E. San Antonio St.); (830) 505-7677; daniella.perez@friocounty.org (from `https://www.co.frio.tx.us/page/elect.home`).

### Hansford — not found
- Elections page (`https://www.co.hansford.tx.us/page/Elections`) has no results for any election; agendas page lists only 2026.
- Records request: Janet Torres, County & District Clerk and Elections Administrator, Hansford County, 15 Northwest Court, Spearman, TX 79081; 806-659-4110; clerk@hansfordcountytx.com (from `https://newtools.cira.state.tx.us/page/hansford.County.Clerk`).

### Hartley — not found
- Closest: `https://newtools.cira.state.tx.us/upload/page/7772/Unofficial%20Results.pdf` (ES&S Electionware summary, "UNOFFICIAL RESULTS", election night 7:22 PM, scanned, 7 pp, county totals by method). Landing page `https://newtools.cira.state.tx.us/page/hartley.Voter.Information`. The official reconciliation form is posted; no canvass or precinct report.
- Records request: Melissa Mead, County Clerk, Hartley County, PO Box 189, Channing, TX 79018; 806-235-3582; mmead@hartleycountytx.gov (from `https://newtools.cira.state.tx.us/page/hartley.County.Clerk`).

### Howard — not found
- Closest: `https://newtools.cira.state.tx.us/upload/page/0454/2024%20November/ENR%20w%20WI.pdf` (ES&S Electionware summary, "UNOFFICIAL RESULTS / ELECTION NIGHT", 7 pp, county totals) and `.../EV%20Results%20w%20WI.pdf` (early voting and mail, county totals). Landing page `https://newtools.cira.state.tx.us/page/howard.Election.Information`. Nov 19, 2024 minutes record the canvass but the report is not attached. A 2022 "Pct Report Canvass.pdf" exists in the same folder tree, so a 2024 one likely exists.
- Records request: Jodi Duck, Elections Administrator, Howard County, PO Box 1069, Big Spring, TX 79721 (2006 FM 700, Big Spring, TX 79720); 432-264-2273; hcvotes@gmail.com (from `https://newtools.cira.state.tx.us/page/howard.Elections`).

### Hudspeth — not found
- Closest: `https://www.co.hudspeth.tx.us/upload/page/0119/2024/general_election_november_2024_hart_intercivic.pdf` (Hart cumulative results report, scanned with OCR layer, 5 pp, county totals by method). Landing page `https://www.co.hudspeth.tx.us/page/Elections%20Results%202020-2025`. The county posted Hart precinct reports for the March 2024 primary and Nov 2025.
- Records request: Brenda Sanchez, County & District Clerk, Hudspeth County, 109 W. Millican St, Sierra Blanca, TX 79851; 915-369-2331; bsanchez@co.hudspeth.tx.us; PIA page `https://www.co.hudspeth.tx.us/page/PublicInformationRequests` (from `https://www.co.hudspeth.tx.us/page/Elections%20Home`).

### Irion — not found
- The county's CivicPlus site (`https://www.co.irion.tx.us/1205/Elections`) posts results from March 2026 onward only (including a precinct-by-precinct PDF, so the county produces them). Nov 12 and Nov 26, 2024 agendas have no canvass item and no minutes are posted.
- Records request: Shirley Graham, County & District Clerk, Irion County, PO Box 270 (209 N. Park View St.), Mertzon, TX 76941; 325-835-2421 ext. 4; shirley.graham@co.irion.tx.us (from `https://www.co.irion.tx.us/1193/County-Clerk`).
