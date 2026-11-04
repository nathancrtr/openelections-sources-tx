# Sources found for the 2024 general election, Batch 3 (Jackson through Zapata)

Searched 2026-11-04. Scope: official precinct-by-precinct results of the November 5, 2024 general election. A county-wide summary alone does not count; it is listed under the county only as context for a records request.

Limits of this session's network: web.archive.org is blocked, and www.co.somervell.tx.us returned 503/connection reset to every method, so those two could change from another network.

## Found (precinct level)

### Polk County

Page: https://polkcotx.portal.civicclerk.com/ (event id 1655, 'Commissioners Court - Special Meeting November 18, 2024'); county results page https://www.polktx.gov/389/Election-Results lists only the unofficial cumulative report

- `Packet - Commissioners Court Special Meeting 2024-11-18 (canvass).pdf` — https://polkcotx.api.civicclerk.com/v1/Meetings/GetMeetingFileStream(fileId=1835,plainText=false)  
  fetched 2026-11-04; SHA-256 `7168439eacfe773c66c3a8d0fc0dca8a3d5b12357f750cae8e811db83c90ae6f`; pdf scanned (with OCR text layer); Polk County Commissioners Court special meeting packet, Nov 18 2024: signed Canvass of Election certificate (p1) + ES&S 'Canvass Results Report', Official Results, run 11/15/2024 (precinct-by-precinct for every contest incl. President and US Senate; 42 of 42 precincts = 22 precincts subdivided by ISD/city; absentee/early/election-day ballots cast per precinct, but candidate votes per precinct are totals only) + Cumulative Results Report Official Results (county totals with method split), 73 pages; official
- `Minutes - Commissioners Court Special Meeting 2024-11-18.pdf` — https://polkcotx.api.civicclerk.com/v1/Meetings/GetMeetingFileStream(fileId=1854,plainText=false)  
  fetched 2026-11-04; SHA-256 `78b5396803c220d243fec80989c8e23b65a322b029060744bd730d186ac30a39`; pdf scanned; Minutes of the Nov 18 2024 special meeting (canvass), 2 pages; official
- `Agenda - Commissioners Court Special Meeting 2024-11-18.pdf` — https://polkcotx.api.civicclerk.com/v1/Meetings/GetMeetingFileStream(fileId=1832,plainText=false)  
  fetched 2026-11-04; SHA-256 `38edac5cb12793e39c6e5d7470c2d1393d19ab39a268fe5e760e9a5930e48b36`; pdf text; Agenda, item 3 'Canvass November 5, 2024 election results', 1 page; official
- `Unofficial Results 11-5-2024.pdf` — https://newtools.cira.state.tx.us/upload/page/9241/Nov%202024/Unofficial%20Results%2011-5-2024.pdf  
  fetched 2026-11-04; SHA-256 `5dff0904333ca520e51d668f83c09ef17a9b4061b797a4e2f35c8b4dfc19de51`; pdf text; ES&S Cumulative Results Report, Unofficial, run 9:40 PM 11/05/2024, county totals with absentee/early/election-day split (same file also at https://www.polktx.gov/DocumentCenter/View/301); unofficial

Precincts seen: 42. Method breakdown: False.

Notes: Precinct-level candidate votes are only in the commissioners-court canvass packet (CivicClerk API stream). It is a scan with an OCR layer; pdftotext output is partially garbled, so numbers should be taken from the page images. Method split exists only for ballots-cast counts per precinct and for county totals, not for candidate votes per precinct. County elections contact (County Clerk/EA Schelana Hock) per https://www.polktx.gov/DocumentCenter/View/211.

## Not found (precinct level): records request needed

### Jackson County

Page checked: https://www.co.jackson.tx.us/page/jackson.VotingElectionInformation

Records request to: Jackson County Clerk (Elections Administration); Katherine M. Respondek; jcclerk@co.jackson.tx.us (open records) / k.respondek@co.jackson.tx.us; 361-782-3563; 115 W. Main St., Room 101, Edna, TX 77957

Notes: County elections page (ezTask/CIRA site, Jackson County Clerk Katherine M. Respondek runs elections; ES&S equipment) posts no results of its own; its only 'Election Results' link goes to the Texas SOS election-night site (https://results.texas-election.com/county), which is county-level only. Pages exist only for 2026 elections; guessed 2024/2025/archive page names return 403. Commissioners Court minutes page lists only Nov 12 and Nov 26, 2024 for FY2024; both downloaded and checked (text PDFs) and neither contains the general-election canvass or any vote figures (minutes were not kept). County news / public notices / county clerk pages have no results files. Web searches for a Jackson County precinct/canvass PDF only surface other counties (Jasper, Hardin) or Jackson Counties in other states. Wayback Machine is blocked from this environment. Records request needed for the official precinct-by-precinct (ES&S) report / canvass.

### Karnes County

Page checked: https://www.co.karnes.tx.us/page/karnes.Elections

What is online (not precinct level):
- `Official Results 11.5.2024.pdf` — https://www.co.karnes.tx.us/upload/page/1033/Current%20Documents/Official%20Results%2011.5.2024.pdf  
  fetched 2026-11-04; SHA-256 `c651a9420542b3086bc4854843237e591a2984763b7474c5a72c0027730abef6`; pdf text; Hart Verity 'Cumulative Results Report - Official Results', General Election 11/5/2024, run 11/18/2024 (canvass day), 8 pages. County-wide totals only (15 of 15 precincts reporting) with Absentee / Early Voting / Election Day split for every contest incl. President and U.S. Senate. NOT broken down by precinct.; official
- `11-18-24 Comm. Crt. Special Meeting.pdf` — https://karnescotx.api.civicclerk.com/v1/Meetings/GetMeetingFileStream(fileId=149,plainText=false)  
  fetched 2026-11-04; SHA-256 `1bde34f8464460c504e04f7c84a90b38aed3390781fc260e1c8da2499870f7f5`; pdf scanned; Agenda (scanned, 2 pages) of the Nov 18, 2024 Commissioners Court special meeting whose item 6 is the canvass of the Nov 5, 2024 General Election. No packet, minutes or precinct returns are attached to this meeting in the CivicClerk portal.; official

Records request to: Karnes County Elections Department; Beth Montalvo, CERA, REO, Elections Administrator; electionsadmin@co.karnes.tx.us; (830) 780-2246; 210 West Calvert, Suite 140, Karnes City, TX 78118

Notes: Only a cumulative (county-wide) official report is posted for Nov 2024. The county elections page does post precinct-level reports for other elections (e.g. '5.26.2026 PRECINCT REPORT.pdf', 'DEM Primary Precinct Results 03.03.2026.pdf', 'Republican Primary Precinct Results 03.03.2026.pdf') but none for the Nov 5, 2024 general; a search-engine hit 'PRECINCT Box Results.pdf' under /upload/page/1033/ now returns 404. Commissioners Court agendas/minutes are on CivicClerk (https://karnescotx.portal.civicclerk.com/): the 11-12-24 and 11-26-24 packets/minutes were checked and contain no canvass returns. Karnes has 15 voting precincts (commissioner pct 1 = 4 & 11; pct 2 = 2,6,7,10,12,13; pct 3 = 1,3,8,15; pct 4 = 5,9,14). Request the Verity 'Precinct Report' / canvass returns from the Elections Administrator. || SECOND PASS (2026-11-04): Playwright listing of https://www.co.karnes.tx.us/page/karnes.Elections (the only elections page; no Archive/Results subpages exist) found no Nov 2024 precinct file; the 2024 general entries are still just Current Documents/Official Results 11.5.2024.pdf (cumulative). Probed ~30 guessed names (11.5.2024 PRECINCT REPORT.pdf, Precinct Report 11.5.24.pdf, Precinct Results 11.05.2024.pdf, General Election Precinct Results 11.5.2024.pdf, PRECINCT Box Results.pdf, etc.) across /upload/page/1033/, /Current Documents/, /Prior Documents/, /Prior Documents/2024/ and /docs/. One hit: https://www.co.karnes.tx.us/upload/page/1033/Prior%20Documents/PRECINCT%20Box%20Results.pdf (HTTP 200; the search-engine-indexed copies at /upload/page/1033/PRECINCT Box Results.pdf on www and newtools both 404). It is NOT results: a 1-page text notice reading 'PRECINCT (BOX) RESULTS ARE AVAILABLE - Due to the size of the Precinct (Box) Report these are available in person at the Karnes County Elections Administration - please come by to view the results or to get copies. 210 W Calvert, Ste. 140, Karnes City, TX 78118, Mon-Fri 8-12 and 1-5' (saved at /tmp/claude-0/-home-user/e8b9568f-2f39-5204-a78e-f8875e08ac54/scratchpad/pass2/karnes_dl/PRECINCT Box Results.pdf, sha256 4623bcbf8f3676c6f8bbcd8d4fadd44729641917c852b7c4b67ddd976ed5b5c9). So the county deliberately does not post the Nov 2024 precinct report online; it must be requested/viewed in person. WebSearch 'site:co.karnes.tx.us precinct 2024' and '"Karnes County" "precinct" "November 5, 2024"' returned only the cumulative Official Results, Notice of Canvass 11.5.2024, polling-location and EV-hours PDFs plus that notice. CivicClerk API (karnescotx.api.civicclerk.com/v1/Events) lists for Nov 2024-Jan 2025: 11-12-24 (agenda+packet), 11-18-24 special (agenda only, no packet/minutes), 11-26-24 (agenda, packet 44pp, minutes 3pp), 12-10-24 (agenda, packet 113pp, minutes), 12-20-24 (agenda, packet 100pp, minutes), 1-14-25; downloaded and text-searched the 11-26, 12-10 and 12-20 packets and minutes: no canvass returns, results report or precinct tables (zero hits for 'Railroad Commissioner', 'Cumulative Results', 'canvass').

### Kent County

Page checked: https://www.co.kent.tx.us/page/kent.Elections

What is online (not precinct level):
- `111324 Agenda.pdf` — https://www.co.kent.tx.us/upload/page/11688/111324%20Agenda.pdf  
  fetched 2026-11-04; SHA-256 `c22e455a2125d3fd858e4c9ae3bcb40744488189ffdb70b2d729840c88ca9ba2`; pdf text; Commissioners Court agenda for Wednesday Nov 13, 2024 (2 pages); item 5 is 'Canvass Nov. 5th Election'. Agenda only; no results, packet or minutes attached.; official

Records request to: Kent County Clerk (also District Clerk / election officer); Craig Harrison; 806-237-3881 (fax 806-237-2300); courthouse 806-237-3373; P.O. Box 9, 101 N Main Street, Jayton, TX 79528

Notes: Kent County (Jayton; county clerk Craig Harrison runs elections; paper ballots hand-counted per local press) has an ezTask site at www.co.kent.tx.us. Its Elections page only carries 2025-2026 documents (2026 primary certified results, 11.3.26 unofficial general results, notices); nothing from 2024. The Agendas page lists agendas only (no minutes) back to March 2024; the Nov 13, 2024 agenda confirms the canvass date but no canvass document is posted. Guessed archive page names return 403. kentcountytexas.us is a parked domain. Web search finds nothing for Kent County, Texas 2024 precinct results (results are swamped by Kent County, Michigan). No e-mail address is published for the clerk (site uses a contact form).

### King County

Page checked: https://www.co.king.tx.us/page/king.County.Clerk

Records request to: King County Clerk; Jammye D. Timmons; 806-596-4412 (fax 806-596-4664); courthouse/judge 806-596-4411; 800 South Baker, P.O. Box 135, Guthrie, TX 79236

Notes: King County (Guthrie, ~135 voters in 2024) has an ezTask site at www.co.king.tx.us. The County Clerk / Public Notices pages post older election documents: 'King Co Elecetion Results.pdf' (scanned, Nov 3, 2020 general, by precinct with EV/ED split for 4 precincts), 'Canvas 2022 Mar Election.pdf', 'Special Election Canvass Report.pdf' (Jan 2021 HD68 special), 'Resolution Canvassing.pdf' (2020 bond election), 2026 primary 'Democratic/Republican Election Totals.pdf' - but nothing for the Nov 5, 2024 general. Commissioners Court agenda page has 4 Nov 2024 and 9 Dec 2024 agendas (scanned; no canvass item, and no mid-November special meeting posted); no minutes are posted. The 2020 file shows the county reports precincts 1-4 with absentee (AT-1..AT-4), EV and ED columns, so a 2024 equivalent likely exists on paper at the clerk's office. No e-mail address published (contact form only).

### Kinney County

Page checked: http://www.co.kinney.tx.us/page/Elections.Archive

What is online (not precinct level):
- `election_results.pdf` — http://www.co.kinney.tx.us/upload/page/0119/2024%20Election/election_results.pdf  
  fetched 2026-11-04; SHA-256 `879e28aadd393eaa9fafad8ff8d26a696b177c656fa81b31285531cec69177c1`; pdf scanned; ES&S Electionware 'Summary Results Report, 2024 General Election, November 5, 2024, Kinney County' marked UNOFFICIAL RESULTS; 11 scanned pages with an OCR text layer (numbers partly garbled). County-wide totals only with Absentee / Early Voting / Election Day columns for all contests incl. President/Vice President and US Senator; '4 of 4' precincts reporting. NOT broken down by precinct.; unofficial

Records request to: Kinney County Clerk / Election Administrator; Rick Alvarado; clerk.ralvarado@co.kinney.tx.us; 830-563-2521 Ext. 3 (fax 830-563-2644); P.O. Box 9, 501 South Ann Street, Brackettville, TX 78832

Notes: The county's 'Past Elections' archive page lists, for Nov 5, 2024, only the unofficial summary report above plus voter rosters (xlsx), notices and sample ballots; no official/canvassed results and no precinct report. The same file is mirrored at https://newtools.cira.state.tx.us/upload/page/0318/2024%20Election/election_results.pdf (identical sha256). Guessed precinct/official filenames in the same folder return 404. Commissioners Court page is an ezTask calendar with no minutes/agenda PDFs posted; public notices page has nothing election-related. Kinney has 4 election precincts (Pct 1 Slater Hall, Pct 2 Frontier Baptist Church, Pct 3 First Baptist Church, Pct 4). Request the Electionware precinct-level report ('Precinct Summary' / Statement of Votes Cast) and canvass from the Election Administrator.

### Kleberg County

Page checked: https://www.co.kleberg.tx.us/page/kleberg.Elections

What is online (not precinct level):
- `Canvass Nov5  2024 General Election Kleberg County.pdf` — https://www.co.kleberg.tx.us/upload/page/6346/Canvass%20Nov5%20%202024%20General%20Election%20Kleberg%20County.pdf  
  fetched 2026-11-04; SHA-256 `acc74a8cd761b0e3b3449cb943c679752e38cd08285985ba299e5b9e608c05df`; pdf scanned; Texas SOS-form 'Canvass Report, 2024 November 5th General Election', 26 pages, one contest per page, COUNTY TOTALS ONLY (no precinct breakdown); signed/sealed 11/15/24 by Salvador Barrera, Election Administrator; President (Trump 5612/Harris 4338) and U.S. Senate (Cruz 5047/Allred 4614) present; scanned image PDF (no text layer); official
- `Official EL45A Nov 5 2024.pdf` — https://www.co.kleberg.tx.us/upload/page/6346/Official%20EL45A%20Nov%205%202024.pdf  
  fetched 2026-11-04; SHA-256 `7f291ce52c3178edeaaea3e2cbcd7d3f44dd729931beab20a40a1641d5f496ff`; pdf scanned; ES&S EL45A 'Summary Rept-Group Detail', Kleberg County General Election November 5, 2024, marked OFFICIAL, run 11/25/24, 4 pages; county totals split Election Day / Early Voting / Mail / Provisional and ballots cast by ballot style (9 styles); header says 'Precincts counted (of 15): 4'; NOT a per-precinct report; scanned image PDF; official
- `EL45A Reort 11052024.pdf` — https://www.co.kleberg.tx.us/upload/page/6346/EL45A%20Reort%2011052024.pdf  
  fetched 2026-11-04; SHA-256 `d1f8407566ac8bf59877b2a19fda7c418c4bc01c4a81ffcfc20faae1ec5a02e3`; pdf scanned; Election-night EL45A summary report (unofficial), 4 pages, county totals with ED/EV/Mail/Prov split; scanned; unofficial
- `Updated unoffical summary report 11052024.pdf` — https://www.co.kleberg.tx.us/upload/page/6346/Updated%20unoffical%20summary%20report%2011052024.pdf  
  fetched 2026-11-04; SHA-256 `462fefbe8d1784fc229bb882f20f143529b6ef58b8d033e338659caa307e86f7`; pdf scanned; Updated EL45A summary report run 11/13/24, marked UNOFFICIAL, 4 pages, county totals with ED/EV/Mail/Prov split; scanned; unofficial
- `ccm.11.25.24.pdf` — https://newtools.cira.state.tx.us/upload/page/6331/ccm.11.25.24.pdf  
  fetched 2026-11-04; SHA-256 `c4e4f2ff1ca0cb520e3e935445434187e8cf1dee4264cbddf42b868adb7b842e`; pdf scanned; Kleberg County Commissioners' Court minutes, regular session Nov 25, 2024, 7 pages; Agenda Item 7 accepts and approves the 'November 5, 2024 General Election Canvass Report from the County Clerk' -- no vote figures attached; scanned; official

Records request to: Kleberg County Elections / County Clerk; Salvador "Sonny" Barrera, III (Election Official / County Clerk); 361-595-8548 (fax 361-593-1355); Kleberg County Courthouse, 700 E. Kleberg Avenue #111, P.O. Box 1327, Kingsville, Texas 78364

Notes: County elections page (ezTask/CIRA) lists the official SOS-form canvass report and ES&S EL45A summary reports for Nov 5 2024, but no precinct-level report (EL30/precinct summary) for this election, although it posts 'Official Precincts Results Report Nov 4 2025' and '2020 Gen Precinct Report' for other elections. Commissioners Court minutes for 11/12, 11/18, 11/21 and 11/25/2024 (County Clerk page) contain no precinct returns. Guessed filenames for a 2024 precinct report all returned 404. Kleberg has 15 precincts per EL45A header. Summary reports show method split (ED/EV/Mail/Provisional) at county level only. All PDFs are scanned images (pdftotext empty). SECOND PASS (2026-11-04): Enumerated all ~330 upload links on co.kleberg.tx.us/page/kleberg.Elections and downloaded every candidate not yet checked: 'docs/ELECTIONS/Election Results - Pct by Pct Report.pdf' (EL30A precinct report, but for the July 14 2020 primary runoff), '614 Precinct Report -Official.pdf' (June 14 2022 special election), '524 Election Results Pct Report.pdf' (May 24 2022 primary runoff), 'Official Results RISD 11052024.pdf' (ES&S summary for Riviera ISD only, run 11/25/24), 'RISD Tabulated Results 11052024.pdf' (RISD trustee totals), 'SGISD 11052024.pdf' (polling-place authorization), 'ED History No signatures 11052024.pdf' (voter history roster). No EL30A/precinct report for the Nov 5 2024 general exists on the page; 20 further guessed filenames (Official Precinct(s) Results Report Nov 5 2024, EL30A ..., etc.) returned 404. County Clerk page lists a second Nov 25 2024 minutes file (ccm11.25.242.pdf, 3 pp) which is only the 5:30 PM CDBG public hearing, and ccm11.21.24.pdf (4 pp, already reviewed in pass 1); Commissioners Court page has no agenda packets online. County News and Public Notices pages have no election uploads. Web search found no Kleberg precinct report on any other host. Still not found.

### Knox County

Page checked: https://www.knoxcountytexas.org/page/knox.elections

Records request to: Knox County & District Clerk (elections); Jeannie Clark, County & District Clerk (Voter Registrar: Laura McCanlies, 940-459-2411, PO Box 47); Cdclerk@knoxcountytexas.org; (940) 459-2441 (fax 940-459-2005); Knox County Courthouse, 100 W Cedar St., P.O. Box 196, Benjamin, TX 79505-0196

Notes: County website (knoxcountytexas.org, ezTask/CIRA) Elections page only carries November 3, 2026 material (notice, sample ballots for precincts 101, 201, 202, 301, 302, 401, EV roster); no results, canvass or archive for 2024. County & District Clerk, Commissioners Court, Public Notices and County Judge pages have no minutes or election documents. co.knox.tx.us does not resolve. Web searches found no official Knox County TX 2024 precinct results (results were for Knox counties in KY/OH/IL/IN). Wayback Machine is blocked by egress policy from this environment. Knox County appears to have 6 voting precincts (101, 201, 202, 301, 302, 401) per the 2026 sample-ballot list.

### Lavaca County

Page checked: https://www.co.lavaca.tx.us/page/Elections

What is online (not precinct level):
- `112524 Meeting Min.pdf` — https://www.co.lavaca.tx.us/upload/page/0121/112524%20Meeting%20Min.pdf  
  fetched 2026-11-04; SHA-256 `e0a7d63df19e47b164fb8e18b91455abb8545c1c823fa7af4b75cf532488132b`; pdf scanned; Lavaca County Commissioners' Court minutes, Nov 25, 2024, 11 pages; item 6 'Acknowledge the completion of the canvass for the November 5, 2024 Election' (10,533 voters) -- no vote figures or precinct returns attached; scanned; official

Records request to: Lavaca County Elections Administrator; Tenia Hudson, Elections Administrator; (361) 798-3594 (fax 361-798-4016); Lavaca County Courthouse Annex, 412 N. Texana, P.O. Box 727, Hallettsville, TX 77964

Notes: The county Elections page now shows only the Nov 3 2026 election; the 'Elections - Archive 2022-2024' page has May 2024 entity elections, May 28 2024 runoff, March 2024 primary (with 'Official Precinct Results'), Nov 2023 and Nov 2022 general -- but NO section for the Nov 5 2024 general election. Guessed upload filenames (e.g. 'Official Precinct Results', '11.5.24 Official Results') returned 404; 'CANVASS.pdf' found in both upload dirs is the May 24 2022 primary runoff canvass. Commissioners Court minutes 11/12/24 and 11/25/24 (Agendas & Minutes Archive) have no precinct returns. County has 11 election-day precincts (101,102,119,208,223,231,309,311,329,416,430). Wayback Machine blocked by egress policy.

### Lipscomb County

Page checked: https://www.co.lipscomb.tx.us/page/lipscomb.ElectionInformation

What is online (not precinct level):
- `2024 General Election Official Cumulative Results-11-13-2024 11-00-57 AM.pdf` — https://www.co.lipscomb.tx.us/upload/page/4352/2024%20General%20Election/2024%20General%20Election%20Official%20Cumulative%20Results-11-13-2024%2011-00-57%20AM.pdf  
  fetched 2026-11-04; SHA-256 `600ccbe8ad1e0c2c4a5af3d7d7a928ca00004511e5d22883f54b2eb20f00c8bb`; pdf text; Hart Verity 'Cumulative Results Report', Lipscomb County General Election Nov 5 2024, marked OFFICIAL RESULTS, run 11/13/2024, 9 pages; COUNTY TOTALS ONLY with Absentee/Early/Election Day split per candidate (Trump 1,125 / Harris 123; Cruz 1,094 / Allred 131); header shows '0 of 10' precincts reporting (Verity artifact) and 7 precincts for countywide contests; text-based; official
- `2024 General Election Unoffical Results.pdf` — https://www.co.lipscomb.tx.us/upload/page/4352/2024%20General%20Election/2024%20General%20Election%20Unoffical%20Results.pdf  
  fetched 2026-11-04; SHA-256 `689c45563c9411318e2ce154e7889e05cff7c30d5a0c3c0791c82b06e57aa12e`; pdf text; Same Verity cumulative report run election night 11/05/2024 9:50 PM, marked Unofficial, county totals with Absentee/Early/ED split, 9 pages; text-based; unofficial

Records request to: Lipscomb County & District Clerk / Election Clerk; Chrissy Dunn, County & District Clerk, Election Clerk; chrissy.dunn@co.lipscomb.tx.us; (806) 862-3091; P.O. Box 70, Lipscomb, TX 79056

Notes: Only a cumulative (county-level) official report is posted for Nov 5 2024; no 'Precinct Results' report, although the county posts Verity 'Precinct Results' PDFs for its 2026 elections. Brute-force guesses of a 'Official Precinct Results-11-13-2024 11-0x-xx AM.pdf' filename all 404. Commissioners Court minutes for 11.12.2024 (canvass) and agendas are linked but return 404 on both www.co.lipscomb.tx.us and newtools.cira.state.tx.us. Lipscomb County has 7 voting precincts (106, 202, 207, 303, 308, 404, 409 per sample ballots/rosters). Method split (absentee/early/ED) exists at county level.

### Loving County

Page checked: https://lovingcountyanddistrictclerk.com/elections-1

Records request to: Loving County & District Clerk (Early Voting Clerk / Elections Officer); Mozelle Carr; Elections@lovingcounty.org; 432-309-9500 Ext. 6 (fax 432-789-2194); P.O. Box 194, 100 Bell Ave., Mentone, TX 79754

Notes: County site co.loving.tx.us has no elections page (only Clerk, Commissioners, Public Notices pages with no election documents). The County & District Clerk's site (GoDaddy-hosted) Elections tab carries only the Nov 3 2026 general election: 'END OF NIGHT RESULTS.pdf' and 'Local Results.pdf' there are the 2026 SOS 'Election Unofficial Results Report' (checked), not 2024. No archive of 2024 results/canvass; 2024 files on img1.wsimg.com have unguessable GUID paths. Commissioners' Court minutes portal (clerk.lovingcounty.org:8082) timed out. Loving County votes in a single combined polling place (Precincts 1-4 combined). Wayback Machine blocked by egress policy.

### Marion County

Page checked: https://marioncountytaxoffice.com/november-5-2024-general-election/

What is online (not precinct level):
- `OFFICIAL-RESULTS.pdf` — https://marioncountytaxoffice.com/wp-content/uploads/2024/11/OFFICIAL-RESULTS.pdf  
  fetched 2026-11-04; SHA-256 `b8dd05df5a347e7505e6474867ce39d7923f22896289e60d21a0aec946c8d6ff`; pdf text; Hart Verity 'Cumulative Results Report', Marion County General/Special Election 11/5/2024, labeled 'Official Results', run 11/13/2024, 9 pages; county-wide totals only (shows '10 of 10' precincts reporting), has President and US Senate; NOT broken down by precinct; no early/ED/mail split.; official

Records request to: Marion County Tax Assessor-Collector / Elections; Karen G. Jones; karen.jones@co.marion.tx.us; (903) 665-3281; 119 W Lafayette, Jefferson, TX 75657

Notes: County elections are run by the Tax Assessor-Collector (marioncountytaxoffice.com). The Nov 5 2024 page posts only the official cumulative (county-total) report plus preliminary/official reconciliation forms; no precinct-by-precinct or canvass report is posted. Site rate-limits (HTTP 429) repeated downloads; the official PDF was retrieved via a single fetch. co.marion.tx.us Commissioners Court page has no minutes/agenda packets online. Clarity site for Marion: 404.

### Mason County

Page checked: https://www.co.mason.tx.us/page/mason.Elections

What is online (not precinct level):
- `Summary Results.pdf` — https://www.co.mason.tx.us/upload/page/0284/Summary%20Results.pdf  
  fetched 2026-11-04; SHA-256 `7cc4d4782dc59638b2760e03a4f13e666acfdde332d676a1b677d8c1244c3b99`; pdf text; ES&S Electionware 'Summary Results Report', TX Mason 241105 General, November 5, 2024, labeled UNOFFICIAL RESULTS, generated 11/05/2024 9:09 PM, 7 pages; county-wide totals only (4 of 4 precincts) with Absentee/Early Voting/Election Day columns; has President and US Senate; NOT by precinct.; unofficial
- `meeting-of-the-commissioners-court-special-meeting_minutes_2024-11-18_193633.pdf` — https://towncloud.io/go/mason-county-tx/agendas/610/minutes/get_agenda_document_link  
  fetched 2026-11-04; SHA-256 `943682084064f994b9ce9909602191d98cb223be91529ffcea3a545fa15458ca`; pdf text; Commissioners Court special meeting minutes 11/18/2024, item 2 'Canvass November 5, 2024 General Election' (motion to accept canvass report as presented by County Clerk); no vote figures attached, 3 pages.; official
- `meeting-of-the-commissioners-court-special-meeting_2024-11-18_193637_combined.pdf` — https://towncloud.io/go/mason-county-tx/agendas/610/pdf_packet/get_agenda_document_link  
  fetched 2026-11-04; SHA-256 `450f65976bd6f4341ea6e4dec54f2b189f8ce4d7449613c38e5e6644e9605ec2`; pdf text; Agenda packet for the 11/18/2024 canvass meeting, 10 pages; contains only the agenda and a courthouse grounds policy, no canvass report.; official

Records request to: Mason County and District Clerk (Elections); Chelsa Armendariz; chelsa.armendariz@co.mason.tx.us; 325-347-5253; 210 Westmoreland St., Mason, TX 76856 (mail: P.O. Box 702, Mason, TX 76856)

Notes: County elections page only posts the unofficial election-night summary for Nov 5 2024 (the link is titled 'Summary Results'); no official or precinct-level report is posted. The TownCloud agenda portal (towncloud.io/go/mason-county-tx) has the 11/18/2024 canvass minutes and packet but the canvass report itself was not attached. Clarity site for Mason: 404.

### Maverick County

Page checked: https://co.maverick.tx.us/elections

Records request to: Maverick County Elections Department (Elections Administrator); Marianna Flores-Garcia; marianna.flores@co.maverick.tx.us; (830) 206-8351; 501 E. Main St., Suite B, Eagle Pass, TX 78852

Notes: County site (co.maverick.tx.us, new site) posts election results only from 2026 onward (May 26 2026 official results, Nov 3 2026 early voting); no 2024 results documents in its R2 file bucket listing. Commissioners Court agenda portal (maverickcounty.nowgroupdigital.com) has agendas only (no packets/minutes) for 11/12, 11/17 (special), 11/25/2024 (canvass of Pct 3A/3B/3C recount) meetings. Only non-official coverage found (Eagle Pass Business Journal county totals). www.co.maverick.tx.us returns 404; co.maverick.tx.us works. Clarity site: 404. SECOND PASS (2026-11-04): Agenda portal maverickcounty.nowgroupdigital.com re-checked for Nov and Dec 2024 (meetings 2024-11-12 regular [pdf id 45], 2024-11-17 special [id 44, whose agenda PDF is actually dated Nov 20 2024 and covers MOUs only], 2024-11-25 regular [id 43], 2024-12-09 regular [41], 2024-12-16 special [42]); each meeting page exposes only an agenda PDF (scanned image) -- /api/pdf/<id>?kind=backup returns 404 for all of them, i.e. no packets/attachments are published for 2024. co.maverick.tx.us /elections lists only 2026 results in its R2 bucket (pub-3ec9fd02caf74c549229cabadbf2564d.r2.dev); the bucket has no listing (404) and guessed 2024 paths (elections/results/2024/Nov_5_2024_Official_Results.pdf etc.) are 404. Web search for the Nov 5 2024 precinct PDF found only Eagle Pass Business Journal articles (county totals) and a boardbook.org document (org=2009, returns HTTP 400). Still not found.

### Morris County

Page checked: https://newtools.cira.state.tx.us/page/morris.2024%202025%20COUNTY%20ELECTIONS

What is online (not precinct level):
- `Official Results for November 5 2024 General Election.pdf` — https://newtools.cira.state.tx.us/upload/page/11264/Official%20Results%20for%20November%205%202024%20General%20Election.pdf  
  fetched 2026-11-04; SHA-256 `90ad080370b3057c822313aec438dcc8b2cf27f8f3ba970c8bcf518f0874e433`; pdf scanned; ES&S Electionware 'Summary Results Report', TX Morris County 241105 General, November 5, 2024, labeled OFFICIAL RESULTS / ALL LOCATIONS, generated 11/18/2024, 4 pages (scanned images, no text layer); county-wide totals only (8 of 8 precincts) with Absentee/Early/Election Day columns; NOT by precinct.; official
- `11.5.2024 Unofficial Results.pdf` — https://newtools.cira.state.tx.us/upload/page/11264/11.5.2024%20Unofficial%20Results.pdf  
  fetched 2026-11-04; SHA-256 `7f2aef6785701e0ba86a93dbf285a2bc0b8a172a63f3a881056fd0a02d992527`; pdf scanned; Election-night unofficial summary results report, 3 pages scanned; county totals only.; unofficial

Records request to: Morris County Clerk (Elections); Brittany Andrews; Brittany.andrews@co.morris.tx.us; 903-645-3911; 500 Broadnax Street, Suite D, Daingerfield, TX 75638

Notes: County Clerk's election page (hosted on newtools.cira.state.tx.us) posts only the official and unofficial summary reports for Nov 5 2024; a 'Summary of Precinct Returns' and 'Canvass Report' are posted for the Nov 4 2025 election but not for 2024. No commissioners court minutes online. morriscountyclerk.org is Morris County NJ (not TX). Clarity site: 404.

### Navarro County

Page checked: https://newtools.cira.state.tx.us/page/navarro.Elections

What is online (not precinct level):
- `11.5.2024 OFFICIAL RESULTS..pdf` — https://newtools.cira.state.tx.us/upload/page/4292/docs/Elections/2024/Nov%205%202024/11.5.2024%20OFFICIAL%20RESULTS..pdf  
  fetched 2026-11-04; SHA-256 `9f7ef519d894ccc80d05222261adb3865bb5f352bb483e07ab9e8f0b3dec526e`; pdf text; ES&S Electionware 'Summary Results Report', 2024 General Election, November 5, 2024, Navarro County, labeled OFFICIAL RESULTS, generated 11/15/2024, 10 pages; county-wide totals (30 of 33 precincts reporting shown) with Absentee/Early Voting/Election Day columns; has President and US Senate; NOT by precinct.; official
- `Item 05 Canvas of General Elections.pdf` — http://navarro.easydocs.us/minutes/LinkedDir/2024/Links%202024-11-19-Special/Item%2005%20Canvas%20of%20General%20Elections.pdf  
  fetched 2026-11-04; SHA-256 `0f20446206c935da6f4db370214835422b99f15c0a02a6b5adf820d50b181246`; pdf scanned; Commissioners Court 11/19/2024 canvass attachment, 12 pages scanned: signed canvass form plus the same 10-page official Summary Results Report; county totals only, not by precinct.; official
- `2024-11-19-Special.PDF` — http://navarro.easydocs.us/minutes/LinkedDir/2024/2024-11-19-Special.PDF  
  fetched 2026-11-04; SHA-256 `d2b62f7a0d4b3fe8c239b52a3c50c6734b31ff7ab93cedea52fda2bece874352`; pdf text; Commissioners Court special meeting minutes 11/19/2024 accepting the canvass of the Nov 5 2024 general election, 1 page.; official
- `Canvass for 11.5.24 General Election.pdf` — https://newtools.cira.state.tx.us/upload/page/4292/docs/Elections/2024/Nov%205%202024/Canvass%20for%2011.5.24%20General%20Election.pdf  
  fetched 2026-11-04; SHA-256 `a4ee8545440a4c5c55d253e193844ce6483c51b1b861a0c4a773da95e8f4390b`; pdf scanned; Signed SOS form 11-14 canvass certificate, 11/19/2024, 1 page; no vote figures.; official
- `11.5.24 Navarro County Official Reconciliation Form.pdf` — https://newtools.cira.state.tx.us/upload/page/4292/docs/Elections/2024/Nov%205%202024/11.5.24%20Navarro%20County%20Official%20Reconciliation%20Form.pdf  
  fetched 2026-11-04; SHA-256 `ba7a7f02c7cfed69e6f8490f33b61a7220a52ca0b181c0b82edaaf53375f25eb`; pdf scanned; Official election reconciliation form, 1 page.; official
- `UNOFFICIAL ELECTION RESULTS.pdf` — https://newtools.cira.state.tx.us/upload/page/4292/docs/Elections/2024/Nov%205%202024/UNOFFICIAL%20ELECTION%20RESULTS.pdf  
  fetched 2026-11-04; SHA-256 `97365013fc9daa3f2606df22bd57cc686533d5fa7ef4bf0e107b2a92d2fb3a8b`; pdf text; Election-night unofficial summary results report (11/05/2024 22:22), 10 pages; county totals only.; unofficial

Records request to: Navarro County Elections Administrator (Elections and Voter Registration); Allie Thomas; 903-875-3330; 601 N. 13th Street, Suite 3, Corsicana, TX 75110 (mail: P.O. Box 1018, Corsicana, TX 75151)

Notes: Navarro posts 'OFFICIAL PCT BY PCT' reports for other elections (Nov 2023, Mar 2022, Mar 2026) but for Nov 5 2024 only the summary report, canvass certificate and reconciliation form are posted. The 11/19/2024 canvass packet on navarro.easydocs.us contains the same summary report. The 'Early Voting Rosters and Election Day Returns' subpage (navarro.Elections.Rosters) returned HTTP 403 to all fetch attempts and could not be checked. Clarity site: 404. || SECOND PASS (2026-11-04): newtools.cira.state.tx.us/page/navarro.Elections now redirects to https://www.co.navarro.tx.us/page/Elections. Opened with Playwright (real Chromium context): the Elections page has only three subpages: Elections.2026, Elections.2025.and.Earlier (same Nov 5 2024 set as before: OFFICIAL RESULTS summary, Reconciliation Form, Canvass certificate, UNOFFICIAL results, Notice of Election, training notice, sample ballot - no PCT BY PCT file; the PCT BY PCT files on that page are for 11/7/2023, 5/6/2023, 3/1/2022 and 5/22/2018 only), and Elections.Rosters (the page that 403'd on pass 1; it loads via Playwright and contains only early-voting roster PDFs for 2019-2026, nothing for Nov 2024). The 'Early Voting Rosters and Elections Day Returns' link is the Civix EVR app (goelect.txelections.civixapps.com/ivis-evr-ui/evr, a voter-roster tool, not results; the ENR app at /ivis-enr-ui/races sits behind a Cloudflare security check). Probed 20 guessed filenames (11.5.2024 OFFICIAL PCT BY PCT RESULTS.pdf, OFFICIAL PRECINCT BY PRECINCT.pdf, PCT BY PCT.pdf, etc.) in both the www.co.navarro.tx.us/upload/page/0129/docs/Elections/2024/Nov 5 2024/ and newtools .../page/4292/... folders: all 404. navarro.easydocs.us: directory listings are disabled (403.14); checked the 2024 minutes index and the showdoc pages for 11-12, 11-18, 11-19, 11-25 and 12-09-2024 meetings - the only election attachment is the 11/19 'Item 05 Canvas of General Elections.pdf' already on file (summary report only); 11-18 Special was an executive-session personnel meeting; 11-25 and 12-09 link lists contain no election items. Web searches ('Navarro County' 'November 5, 2024' precinct; 'PCT BY PCT' 2024) return only the files already recorded. County sitemap lists no other Elections pages.

### Pecos County

Page checked: https://www.co.pecos.tx.us/election-information-past-elections/

What is online (not precinct level):
- `Official-Results-for-2024-General-Election-20241105.pdf` — https://www.co.pecos.tx.us/wp-content/uploads/2024/11/Official-Results-for-2024-General-Election-20241105.pdf  
  fetched 2026-11-04; SHA-256 `6e8d490c902368e80e006178efd108e27c5f6b5b58971951c8e510bbfab75e55`; pdf scanned; ES&S Electionware Summary Results Report, OFFICIAL RESULTS, General Election Nov 5 2024, run 11/15/2024, 8 pages; county totals only with Absentee/Early/Election Day split; 9 of 9 precincts reporting but no per-precinct breakdown; official
- `Official-Results-20241105.pdf` — https://www.co.pecos.tx.us/wp-content/uploads/2024/11/Official-Results-20241105.pdf  
  fetched 2026-11-04; SHA-256 `56b55b732232dae0448b5fe358fa1df3ed594d748cab535a5b5d58b500b24684`; pdf scanned; Earlier ES&S Summary Results Report labeled OFFICIAL RESULTS, run 11/12/2024, 7 pages; county totals only with method split; official
- `Preliminary-Election-Reconciliation-Official-Totals-20241105.pdf` — https://www.co.pecos.tx.us/wp-content/uploads/2024/11/Preliminary-Election-Reconciliation-Official-Totals-20241105.pdf  
  fetched 2026-11-04; SHA-256 `e52a1e6392b5ad74d13a1f991eedf302a9f7f447344c264f3749e0f5b3783228`; pdf scanned; SOS Form 12-2 Election Reconciliation - Official Totals, signed Sophia Franco 11/12/2024, 1 page; ballot counts only; official

Records request to: Pecos County Elections Office; Sophia Franco, Election Administrator; sophia.franco@co.pecos.tx.us; (432) 336-2115 office; (432) 434-1554 cell; 200 S. Nelson St, Fort Stockton, TX 79735

Notes: County posts only an ES&S Summary Results Report (county totals, 9 precincts reporting) for Nov 5 2024. No precinct-by-precinct report found on the county site (WordPress media search for 'precinct' shows the county began posting 'Precinct-by-Precinct' reports only for the 2026 primaries), no commissioners-court canvass packet online, no Clarity/ENR page. President and US Senate are present in the summary. Not acceptable under spec (county total only).

### Presidio County

Page checked: https://www.co.presidio.tx.us/page/presidio.Election.Information

What is online (not precinct level):
- `BigBendSentinel_Presidio_County_Unofficial_2024_Election.csv` — https://docs.google.com/spreadsheets/d/1VlhNEXT6_GHf0tKfPXXoE47ZujyZ0HG2KtqlMLAj7fE/export?format=csv  
  fetched 2026-11-04; SHA-256 `1582b9c3b8e3a9dcd12859d84efb1b050c0e2fe0bf5420925e8648c35b794972`; csv; Big Bend Sentinel (newspaper) Google Sheet 'Presidio County Unofficial 2024 Election': Nov 5 2024 general, President and US Senate, by precinct PCT 1-7 with EARLY VOTING section (and possibly election day/total sections further down). NOT an official county document.; unofficial
- `cc_approved_minutes_november_13_2024.pdf` — https://www.co.presidio.tx.us/upload/page/4702/2024/cc_approved_minutes_november_13_2024.pdf  
  fetched 2026-11-04; SHA-256 `b71f788a4849a91956a207745c79fd0cf4aa3965cb3f841704aedf17134ee2e7`; pdf scanned; Commissioners Court approved minutes Nov 13 2024, 6 pages; no canvass item or vote totals; official
- `cc_approved_minutes_november_20_2024.pdf` — https://www.co.presidio.tx.us/upload/page/4702/2024/cc_approved_minutes_november_20_2024.pdf  
  fetched 2026-11-04; SHA-256 `29b6290b82303fa5606a794d007c90d6a89e2c06845c3cad9c6e379b363c7798`; pdf scanned; Commissioners Court special meeting minutes Nov 20 2024, 6 pages; no canvass item or vote totals; official

Records request to: Presidio County Clerk (County & District Clerk conducts elections); Carolina Catano, County Clerk; carolina.catano@co.presidio.tx.us; (432) 729-4812; P.O. Box 789, Marfa, TX 79843 (Courthouse, 300 Highland St., Marfa, TX 79843)

Notes: County elections page posts 2024 March primary results and 2020/2016 general results but nothing for Nov 5 2024 general; Nov 13 and Nov 20 2024 commissioners court minutes contain no canvass. Only precinct-level source found is the Big Bend Sentinel's unofficial spreadsheet (7 precincts), which does not meet the 'official' requirement. precincts_seen refers to that unofficial sheet.

### Real County

Page checked: https://www.co.real.tx.us/page/real.Elections

What is online (not precinct level):
- `2024_november_election_canvass_report.pdf` — https://www.co.real.tx.us/upload/page/0250/docs/2024/2024_november_election_canvass_report.pdf  
  fetched 2026-11-04; SHA-256 `85f8ad9d9e4e9ffbd53f5290508886d5a5a14ec136ba3a90231a192555e5c5ef`; pdf scanned; Texas SOS 'Canvass Report, 2024 November 5th General Election', signed by Dann Green, Election Administrator, 11/13/2024, 25 pages; county totals per contest only (1,969 voters), no precinct breakdown; official
- `2024_november_05_election_results.pdf` — https://www.co.real.tx.us/upload/page/0250/docs/2024/2024_november_05_election_results.pdf  
  fetched 2026-11-04; SHA-256 `9f3e66af72e0f01edea0c493d0201a7b70169dbfb50b425a437a5c926755bd57`; pdf text; ES&S Electionware Summary Results Report, UNOFFICIAL, 11/05/2024 9:52 PM, 5 pages; county totals with Absentee/Early/Election Day split; President and US Senate present; unofficial

Records request to: Real County Elections Office (County & District Clerk); D'Ann Roosa (signed 2024 canvass as Dann Green), County/District Clerk & Election Administrator; (830) 232-5202; P.O. Box 750, 146 S. US Hwy 83, Leakey, TX 78873

Notes: County posts an official SOS canvass report and an unofficial summary, both county-level only (Real County has 5 precincts). No precinct-level report, canvass minutes with precinct returns, or ENR page found.

### Roberts County

Page checked: https://www.co.roberts.tx.us/page/roberts.elections

Records request to: Roberts County Clerk / Voter Registrar; Debra Shewmake, County & District Clerk, Voter Registrar; debra.shewmake@co.roberts.tx.us; (806) 868-2341; fax (806) 868-3381; Roberts County Courthouse, 300 E. Commercial St., Suite 104, Miami, TX 79059 (P.O. Box 477)

Notes: County elections page currently posts only the Nov 3 2026 'Election Day Results.pdf' (scanned ES&S cumulative report, 2026) plus notices; no 2024 results, no commissioners-court minutes online, no ENR page. Web search hits for 'robertscosd.gov' canvass minutes are Roberts County, SOUTH DAKOTA, not Texas. Third-party aggregators show ~570 total 2024 presidential votes.

### Runnels County

Page checked: https://newtools.cira.state.tx.us/page/runnels.Elections

What is online (not precinct level):
- `commissioner-s-court-regular-meeting_minutes_2024-11-12_155101.pdf` — https://towncloud.io/go/runnels-county-tx/agendas/207/minutes/get_agenda_document_link  
  fetched 2026-11-04; SHA-256 `4c37efc4c0e61102413e7ad1983ae155550764e349785cebea8f042f6b68003c`; pdf text; Runnels County Commissioners Court minutes, Nov 12 2024 regular meeting, 5 pages; item 6 records an order to canvass the Nov 5 2024 General Election returns but NO vote figures are attached (the 85-page agenda packet for that meeting also contains no election results).; official

Records request to: Runnels County Elections Administrator; Kelley Berry; kelley.berry@runnelscounty.org; 325-365-5027; 600 Strong Avenue, Ballinger, TX 76821

Notes: County elections page (co.runnels.tx.us redirects to newtools.cira.state.tx.us/page/runnels.Elections) has an 'Archived Election Results' section listing only 'November 2025.pdf' and 'May 2025 Jail Bond Election Precinct Results.pdf'; no Nov 2024 general election file is posted. Commissioners court agendas/minutes/packets are on towncloud.io (Nov 7, Nov 12, Nov 26 2024 meetings checked); the Nov 12 2024 minutes record the canvass order but include no tabulation. Guessed upload paths for a Nov 2024 results PDF all 404. Wayback Machine is unreachable from this environment (web.archive.org connection reset). Local radio KRUN (krunam.com) only has county-total coverage. The county has 10 precincts per its polling-place list (1,3,4,5,6,7,8,9,10 + Pct 2 absent in 2026 list).

### Schleicher County

Page checked: https://www.schleichercounty.gov/page/Elections.Archive

Records request to: Schleicher County and District Clerk (Elections); Marsha L. Maskill; scclerk@co.schleicher.tx.us; 325-853-2833; PO Box 846, 2 South Divide, Eldorado, TX 76936

Notes: The 2024 section of the county's Past Elections page ('General Election for County Officers - November 5, 2024') links 'UNOFFICIAL ELECTION NIGHT RESULTS' at http://www.schleichercounty.gov/upload/page/0086/UNOFFICIAL%20RESULTS.pdf, but that file has been overwritten: it now contains the Texas SOS-format 'Election Unofficial Results Report, 2026 November General Election, November 03, 2026' for Schleicher County (4 pages, text-based, by-method split but county totals only). No canvass/official 2024 file is posted; 'OFFICIAL RESULTS.pdf' at the same folder is the Nov 7 2023 constitutional election; 'Canvass.pdf' is the Nov 2025 election. Commissioners court minutes for 11.12.2024 (sets canvass for Thu Nov 14 2024 2pm) and 11.25.2024 contain no vote figures; no minutes for a Nov 14 2024 special meeting are posted. County has 4 precincts (precinct-level sample ballots 1-4 posted; the 2025 election has per-precinct result PDFs, so the county likely holds per-precinct 2024 reports). Wayback unreachable from this environment.

### Shackelford County

Page checked: https://www.shackelfordcounty.org/page/shackelford.Elections

Records request to: Shackelford County Clerk (Elections); Cheri Hawkins; cheri.hawkins@shackelfordcounty.org; 325-762-9415; P.O. Box 2109, 225 S. Main St., Albany, TX 76430

Notes: The county elections page currently carries only 2026 and 2025 material (Nov 2026 general election notices, May 2026 runoff, March 2026 primary reconciliation, post-election hand-count audit certifications); no Nov 5 2024 general election results or canvass are posted and earlier search snippets indicate the page once listed 2024 primary results only. The 2020 general cumulative report exists at /upload/page/8566/2020 Elections/Shackelford Elections.PDF, showing the county does post Hart-style cumulative reports when it chooses to. Meetings page lists only agendas (2025-2026), no minutes; /page/minutes returns 403. The Albany News November 2024 archive (3 pages) has no results article indexed; a site search for 'canvass' returns nothing for 2024. Upload filenames on this site are timestamp-based and cannot be guessed. Wayback unreachable from this environment. County has 7 precincts (101, 202, 303, 307, 404, 405, 406 per polling notices).

### Shelby County

Page checked: https://www.co.shelby.tx.us/page/shelby.Elections

What is online (not precinct level):
- `11-5-24 unofficial results Shelby County.pdf` — https://www.co.shelby.tx.us/upload/page/2753/2024/11-5-24%20unofficial%20results%20Shelby%20County.pdf  
  fetched 2026-11-04; SHA-256 `63d38d91e5f81faf1480be73a2ac9d0f3ffc5c8f864c2d5d05f8007007a30889`; pdf scanned; ES&S ElectionWare 'Summary Results Report, TX Shelby 241105 General 6110, November 5, 2024', marked UNOFFICIAL RESULTS, 7 pages, scanned image (no text layer). County totals only with Absentee / Early Voting / Election Day split; includes President and US Senator and City of Center / Center ISD races. NOT precinct-level.; unofficial

Records request to: Shelby County Elections Administrator; Nancy Adams; nancy.adams@co.shelby.tx.us; 936-598-5340; 200 San Augustine Street, Box 9, Center, TX 75935

Notes: Only the election-night ES&S summary (county totals by method) is posted for Nov 5 2024; no 'Precinct by Precinct' report or canvass is posted for 2024 even though the county posts such reports for 2026 primaries ('Pct by Pct Unofficial Results.pdf'). Local news site scttx.com ('November 5 General Election ... Results (All Boxes In)', Nov 5 2024) likewise shows only Early/Election Day/Total county figures. Commissioners Court page has no minutes or agendas. Guessed 2024 precinct-report filenames 404. County has 15 precincts (1N, 1S, 1SE, 1SW, 1W, 2, 3, 4, 5, 6, 7, 8, 9N, 9S per sample-ballot list). Wayback unreachable from this environment.

### Sherman County

Page checked: https://www.shermancountytx.gov/page/Elections.2025.and.Earlier

What is online (not precinct level):
- `Official Canvassed Totals Nov 5th 2024.pdf` — http://www.shermancountytx.gov/upload/page/0109/Official%20Canvassed%20Totals%20Nov%205th%202024.pdf  
  fetched 2026-11-04; SHA-256 `f0ba54290cbb1de9727698de72370a33fbd74ef756c084adef39ebde783055f4`; pdf text; ES&S ElectionWare 'Summary Results Report, TX Sherman 241105 General 6110, November 5, 2024', marked OFFICIAL RESULTS, 4 pages, text-based. County TOTAL column only (no precinct columns, no early/ED/mail split); 905 ballots cast; President (Trump 817, Harris 70) and US Senate included; statistics show 7 of 7 precincts reporting. NOT precinct-level.; official

Records request to: Sherman County and District Clerk (Elections); Laura Rogers; laurarogers@co.sherman.tx.us; 806-366-2371; PO Box 270 / 701 N. 3rd Street, Stratford, TX 79084

Notes: The only Nov 5 2024 file on the county site is the official canvassed summary (county totals). The site has no commissioners court minutes/agenda documents online (Commissioners Court, County Judge, Public Notices and County News pages carry no meeting documents). Guessed precinct-report filenames 404. County has 7 precincts per the report statistics. Wayback unreachable from this environment.

### Somervell County

Page checked: https://www.co.somervell.tx.us/page/somervell.Elections

Records request to: Somervell County Elections Administrator; Christy Covey; elections@co.somervell.tx.us; 254-897-9470; 107 N E Vernon St, Glen Rose, TX 76043 (mailing: PO Box 1355, Glen Rose, TX 76043)

Notes: The county website (www.co.somervell.tx.us) could not be reached from this environment at all: HTTPS connections were reset at the TCP level, HTTP returned 503, WebFetch returned 503, Playwright got 502 from the egress gateway; www.somervellcounty.org was refused by the proxy; newtools.cira.state.tx.us mirror paths returned 403; web.archive.org is blocked. Web searches found no Somervell precinct results on any other host (no Clarity/ES&S vendor page, no canvass packet on destinyhosted/boardbook), only third-party aggregators (city-stats, txelectionresults, Ballotpedia). Status should be re-tried from a network that can reach co.somervell.tx.us. Contact below is from search-engine snippets of the county Elections page / third-party directories because the county site itself was unreachable. SECOND PASS (2026-11-04): www.co.somervell.tx.us and co.somervell.tx.us (47.44.199.3) still reset the TLS connection immediately after the proxy CONNECT (curl and WebFetch; HTTP returns 503); newtools.cira.state.tx.us/page/somervell.Elections returns 403 (curl and WebFetch); web.archive.org is blocked from this environment and third-party reader/cache proxies are not permitted. Alternate hostnames (somervellcounty.org, somervellcountytx.gov) do not resolve/connect. Web searches (site:co.somervell.tx.us, site:newtools.cira.state.tx.us somervell, Glen Rose Reporter, commissioners court canvass packet) surfaced no Somervell upload URLs and no precinct results on any other host -- only City of Glen Rose council packets (city, not county) and aggregator county totals. Still not found; needs a retry from a network that can reach co.somervell.tx.us or a records request.

### Sterling County

Page checked: https://www.sterlingcotx.gov/page/Elections%202019-2025

Records request to: Sterling County Clerk (county elections officer); Jerri McCutchen, County Clerk; jerri.mccutchen@co.sterling.tx.us; 325-378-5191; P O Box 55, 609 4th Avenue, Sterling City, TX 76951

Notes: County site (www.co.sterling.tx.us -> www.sterlingcotx.gov) 'Elections 2019-2025' page lists Nov 2025 constitutional-amendment hand-count audit, May 2024 runoff 'Election Unofficial Results Report', March 2024 primary results, 2022 and 2020 unofficial results, and an Aug 2024 Order of Election, but NO results file of any kind for the Nov 5, 2024 general election. Agendas and Commissioners Court pages carry no minutes/canvass packets. No Clarity/ES&S vendor page found. Web searches surface only third-party aggregators (city-stats, txelectionresults).

### Trinity County

Page checked: https://www.co.trinity.tx.us/page/trinity.Elections2

What is online (not precinct level):
- `11.26.24 Agenda.pdf` — https://www.co.trinity.tx.us/upload/page/10760/2024/11.26.24%20Agenda.pdf  
  fetched 2026-11-04; SHA-256 `c08981bbfe3c78236243ad446e5bb981a92a49bcb9790f9982ea955fa867282e`; pdf text; Commissioners Court agenda for 11/26/2024, 2 pages; item 6 'Act and Approve Canvass for the November 5, 2024 General Election'. Agenda only, no vote data.; official

Records request to: Trinity County Elections Administrator; Priscilla Rasbeary; 936-642-3959; 215 W. 1st St., Groveton, TX 75845 (mailing: PO Box 158, Groveton, TX 75845); fax 936-642-0155

Notes: County elections page (trinity.Elections2) only carries current Nov 2026 election notices; its 'Archived Election Results' page (trinity.archived.elections) has only Nov 2016/Nov 2018 canvass tally xlsx and March 2022 primary canvass PDFs, nothing for 2024. Agendas page (trinity.Agendas2022) has agendas but no minutes; no minutes/canvass packet is posted anywhere on the site (guessed Minutes pages return 403/404). Public Notices page has nothing election-related. Note: most search hits for 'trinitycounty.org' are Trinity County, CALIFORNIA, not Texas. No vendor results site found.

### Upton County

Page checked: https://www.co.upton.tx.us/page/upton.elections

Records request to: Upton County Elections Administrator; Hayley Abalos; habalos@co.upton.tx.us; (432) 693-2014; 1000 N. Rankin St. (physical); P.O. Box 65, Rankin, TX 79778 (mailing)

Notes: County elections page (www.co.upton.tx.us/page/upton.elections) only carries the current cycle (Nov 2026 general unofficial results/reconciliation, March 2026 primary) plus 2026 polling-place notices; no 2024 archive. County Clerk, Commissioners Court and County News pages hold no minutes or canvass packets. No vendor results site found. Only third-party aggregators appear in search.

### Uvalde County

Page checked: https://www.uvaldecountyelections.com/election-results

What is online (not precinct level):
- `e2f0cf_6be2d3b1d9cc44efbd1ff8d26dda7852.pdf` — https://www.uvaldecounty.gov/_files/ugd/e2f0cf_6be2d3b1d9cc44efbd1ff8d26dda7852.pdf  
  fetched 2026-11-04; SHA-256 `6c3b38a9cb0d6d233ecb191e724a8f7b43fbd22c0d96bf596381e54f116dff47`; pdf text; Commissioners Court minutes, Nov 15 2024, 1 page: canvass of the 11/5/2024 General Election approved 3-0, 'precinct returns' presented and 'See Attached' -- but the attachment/exhibit is NOT included in the posted PDF. No vote data.; official

Records request to: Uvalde County Elections Administrator; Christine White (EA in Nov 2024 was Melissa Jones per canvass minutes); elections@uvaldecounty.gov; 830.591.2724; 124 E. North St., Uvalde, TX 78801 (mailing: #2 Courthouse Square, Uvalde, TX 78801); fax 830.261.5687

Notes: Elections office site (uvaldecountyelections.com) Election Results page lists 2026 general, May 2026 runoff, May 2026 local, March 2026 primary files only (the 'Precinct by Precinct Results (Official)' PDF there is the May 26, 2026 primary runoff; the unofficial precinct PDF is the Nov 3, 2026 general). Its 'Past Election Results' Google Drive folder (1zquLwDN750qX72gN82snb0EXwhJS6nnq, 72 items) has precinct/canvass/cumulative files for 2014-2023, March 2024 primary, May 2024 runoff, Nov 2025 and 2026 -- but NOTHING for the Nov 5, 2024 general. County site agendas-minutes-2024-2025 page has the 11-15-2024 canvass agenda and minutes only; the minutes say exhibits are attached but the PDF is 1 page. Old site uvaldecounty.com/images/elections_admin/... is gone (404) and web.archive.org is blocked from this environment. ENR vendor is Civix (goelect.txelections.civixapps.com) which only shows current elections. || SECOND PASS (2026-11-04): Opened the 'Past Election Results' Drive folder (1zquLwDN750qX72gN82snb0EXwhJS6nnq, titled 'Historic Election Results') with Playwright, scrolled until the count stopped growing: 73 items = 72 PDFs/Docs + one subfolder ('2018.09.18 Special State Senate Runoff'). Full name list saved at /tmp/claude-0/-home-user/e8b9568f-2f39-5204-a78e-f8875e08ac54/scratchpad/pass2/uvalde_drive_list.txt. 2024 items are only: 2024.03.05 OfficialCanvass Results.pdf, 2024.03.05 OfficialCumulative Results.pdf, 2024 Primary Runoff Canvass Results.pdf. Nothing named November/11.05/General/Canvass/Precinct for Nov 2024 (the next items chronologically are 11.04.2025 Canvass Results.pdf and '11.08.2022 Canvass Results-11-10-2025...'). Elections site (Wix) pages-sitemap lists only candidate-information, contact, election-information, election-results, legal-notices, sample-ballots, sampleballots, text-my-gov, voter-information; election-results and legal-notices re-listed via Playwright: 2026 files only plus the same Drive link and the Civix ENR link (goelect.txelections.civixapps.com/ivis-enr-ui/races, which is behind a Cloudflare security check and shows only current elections anyway). County site (uvaldecounty.com now redirects to uvaldecounty.gov) agendas-minutes-2024-2025 page: Agenda 11-15-2024 (1 page, item 1 'Canvass results of the November 5th, 2024 election'), Minutes 11-15-2024 (1 page, already on file, exhibit not included), Agenda/Minutes 11-25-2024 (4 pp), 12-09-2024 (5 pp), 12-16-2024 (2 pp): every 'See Attached' exhibit is omitted from the posted minutes PDFs; no packet PDFs exist on the site. The agendas page 'Archives' Drive folder (1yigbDXeXR9Len4kayXzpIBqU5GTwIpiL, 'COMMISSIONERS COURT') contains only AGENDAS/MINUTES folders for 2008-09 through 2022-23. uvaldecounty.gov/elections page has no documents. Web searches ('Uvalde County' Nov 5 2024 precinct canvass; site:uvaldecountyelections.com 2024) return only the 11-15-2024 minutes/agenda and news pages. Conclusion unchanged: the Nov 5 2024 precinct returns exist as the canvass exhibit but are not posted anywhere online; request from the Elections Administrator.

### Wheeler County

Page checked: https://www.wheelercounty.texas.gov/page/Elections.2018-2025

What is online (not precinct level):
- `OfficialResults.PDF` — https://www.wheelercounty.texas.gov/upload/page/0103/2024/2024-11-05/OfficialResults.PDF  
  fetched 2026-11-04; SHA-256 `6409996ca31e7ea5ae6c4aa246c8cc307aa5d12e71a04b0a89aa8234756ba50c`; pdf scanned; Hart Verity-style 'Cumulative Results Report', Wheeler County General Election 11/5/2024, run date 11/21/2024, 9 pages, OCR text layer present. COUNTYWIDE TOTALS ONLY (header shows 'Precincts Counted 0 of 5'); absentee/early/election-day split; President and U.S. Senate present. Labeled Official Results on the county page.; official
- `Preliminary Election Reconciliation-UNOFFICIAL TOTALS.PDF` — https://www.wheelercounty.texas.gov/upload/page/0103/2024/2024-11-05/Preliminary Election Reconciliation-UNOFFICIAL TOTALS.PDF  
  fetched 2026-11-04; SHA-256 `d03a029bdadc9f1af211201ee15ad2b583db9ac53c564408165aa6d009eebed6`; pdf text; SOS Form 12-1 Preliminary Election Reconciliation, unofficial totals, 1 page; ballot counts only, no candidate results.; unofficial
- `M-2024-11-12.pdf` — https://www.wheelercounty.texas.gov/upload/page/0080/docs/2024/M-2024-11-12.pdf  
  fetched 2026-11-04; SHA-256 `2816f25e6f151e4f3d8beca8730777de05e1cfd7369ca557f5453c5584e5800a`; pdf text; Commissioners Court minutes 11/12/2024, 2 pages; records approval of the canvass report for the November 2024 General Election but contains no vote figures.; official
- `M-2024-11-25.pdf` — https://www.wheelercounty.texas.gov/upload/page/0080/docs/2024/M-2024-11-25.pdf  
  fetched 2026-11-04; SHA-256 `e7673ae3fe223ecf955e185abff0c3b1c9bc4eeb6f294c57592cc985cea6f4f0`; pdf text; Commissioners Court minutes 11/25/2024, 2 pages; no election results.; official

Records request to: Wheeler County Clerk / Elections (Wheeler County Courthouse); (806) 826-5961; 401 S. Main Street, Wheeler, Texas 79096

Notes: County posts only the cumulative (countywide) official results report; the 2024-11-05 upload folder (also mirrored at newtools.cira.state.tx.us/upload/page/4632/...) has no precinct-level report, and the canvass minutes carry no attachment. The county has 5 voting precincts (sample ballots 101/201/301/401 plus 301-MISD variant). Mirror of OfficialResults.PDF also at https://newtools.cira.state.tx.us/upload/page/4632/2024/2024-11-05/OfficialResults.PDF (www.wheelercounty.texas.gov/upload/page/4632/... returned 404 to curl).

### Wilbarger County

Page checked: https://www.co.wilbarger.tx.us/page/Elections.Past

What is online (not precinct level):
- `doc019_11.19.pdf` — https://www.co.wilbarger.tx.us/upload/page/0109/2024/doc019_11.19.pdf  
  fetched 2026-11-04; SHA-256 `908561290cfe1d808f73c3eb59b41f5b6db296e80ee9046aa3591305253f7789`; pdf scanned; 'Cumulative Results Report WILBARGER COUNTY Official Results', 2024 November 5th General Election, run 11/8/2024, 6 pages, image-only scan (no text layer; OCR works). COUNTYWIDE TOTALS ONLY ('Precincts Reporting 10 of 10'); absentee/early/election-day split; President and U.S. Senate present. Linked as 'Official Results'.; official
- `unofficial_results_1152024.pdf` — https://www.co.wilbarger.tx.us/upload/page/0109/2024/unofficial_results_1152024.pdf  
  fetched 2026-11-04; SHA-256 `450272eeeaae1abbf74cb6c77fd939eb7ac96e45b493dd09f6491b0845a77f82`; pdf scanned; Election-night unofficial cumulative results, 11/5/2024, 6 pages, scanned; countywide totals only.; unofficial

Records request to: Wilbarger County Clerk / Elections Administrator; Jana Kennon; jkennon@co.wilbarger.tx.us; 940-552-5486; 1700 Wilbarger Street, Room 15, Vernon, TX 76384

Notes: Only cumulative reports are posted (official and unofficial); no precinct-level report. County has 10 precincts per the official report header (sample ballots posted for precincts 1, 19, 20, 21 with ISD variants). The county website has no commissioners court minutes/agenda archive online (Commissioners Court page lists meeting times only), so no canvass packet was found.

### Willacy County

Page checked: https://www.willacy.gov/page/willacy.Elections

What is online (not precinct level):
- `11142024 Regular Meeting.pdf` — https://www.willacy.gov/upload/page/6514/Minutes/FY24-25 Minutes/11142024 Regular Meeting.pdf  
  fetched 2026-11-04; SHA-256 `8def715aa33d4633be32c9aefba043978c8113c94dc23e779e6a5b725c0b60ba`; pdf scanned; Commissioners Court 11/14/2024 regular meeting document, 5 pages, scanned; no election canvass content.; official
- `11182024 Regular Meeting.pdf` — https://www.willacy.gov/upload/page/6514/Minutes/FY24-25 Minutes/11182024 Regular Meeting.pdf  
  fetched 2026-11-04; SHA-256 `e3ea832b4c86ff843b800cc63bf1c61c912bfca7613dab78321130472f497ea6`; pdf scanned; Commissioners Court 11/18/2024 special meeting, 1 page, scanned; agenda item 3 'Approval to canvas votes for the Willacy County General Elections held on November 5, 2024' but no results attached.; official
- `11252024 Regular Meeting.pdf` — https://www.willacy.gov/upload/page/6514/Minutes/FY24-25 Minutes/11252024 Regular Meeting.pdf  
  fetched 2026-11-04; SHA-256 `ae96c531f524731641857639d884025fe793999de8a52ae6ead773a9b9e7bbed`; pdf scanned; Commissioners Court 11/25/2024 regular meeting, 3 pages, scanned; no election results.; official

Records request to: Willacy County Elections Administrator; Christina Rodriguez; elections.administrator@willacy.gov; (956) 689-2387; 190 N. 3rd St., Room 158, Raymondville, Texas 78580

Notes: The county Elections page (willacy.gov, redirected from co.willacy.tx.us) lists only 2026 and 2016/2018 documents; no 2024 results of any kind are posted. Commissioners Court minutes for the 11/18/2024 canvass meeting are a one-page posting with no attached returns. The only 2024 results found online are the Willacy County Navigation District's unofficial cumulative totals for its own board races (willacynavigation.gov), which are not county precinct results.

### Young County

Page checked: https://www.co.young.tx.us/page/young.Elections

What is online (not precinct level):
- `unofficial_cumulative_results1152024.pdf` — https://www.co.young.tx.us/upload/page/2681/2024/unofficial_cumulative_results1152024.pdf  
  fetched 2026-11-04; SHA-256 `eefa79d1d70e3df37592d7969aa9680b3a6f3f7d2c92bba45c90a8bb67fbea36`; pdf text; Hart Verity 'Cumulative Results Report', Young County General Election 11/5/2024, run 9:21 PM 11/05/2024, 38 pages, text-based. Header says 'Unofficial Results' (body stamped 'OFFICIAL RESULTS' but linked as UNOFFICIAL). COUNTYWIDE TOTALS ONLY ('Precincts Reporting 0 of 12'); absentee/early/election-day split; President and U.S. Senate present.; unofficial
- `commissioners_court_minutesnovember_12_2024.pdf` — https://www.co.young.tx.us/upload/page/2054/2024/commissioners_court_minutesnovember_12_2024.pdf  
  fetched 2026-11-04; SHA-256 `31f1f92c6aeacd0fbbab576c5d7f500767093482732fa63f680bee105a997ef8`; pdf scanned; Commissioners Court minutes 11/12/2024, 4 pages, scanned; no canvass or election results found by OCR.; official
- `commissioner_court_minutes_11252024-young.pdf` — https://www.co.young.tx.us/upload/page/2054/2024/commissioner_court_minutes_11252024-young.pdf  
  fetched 2026-11-04; SHA-256 `6fb25a30fc77cb2ee33ffd702c9a238e0ce889523a9986ff77e6266deacb400f`; pdf scanned; Commissioners Court minutes 11/25/2024, 3 pages, scanned; no canvass or election results found by OCR.; official

Records request to: Young County Elections Administrator; Kaitlyn Mosley; k.mosley@youngcounty.org; 940-521-9483; 417 Second St, Suite 105, Graham, TX 76450

Notes: Elections page links only the election-night UNOFFICIAL cumulative report for Nov 5 2024; no official/canvass report was posted for this election (the county did post 'FINAL.Canvass Results' PDFs for 2020 and an official primary report for March 2024, so canvass reports exist in its system). County has 12 precincts per the report header. Nov 12 and Nov 25 2024 commissioners court minutes contain no canvass; no other November 2024 meeting minutes are listed. Guessed filenames for a 2024 canvass returned 404. SECOND PASS (2026-11-04): Listed every upload link on co.young.tx.us/page/young.Elections (68 uploads; 2024 folder holds only the unofficial cumulative, sample ballots, notices/orders and november_5th_election.pdf, which is the Pct 5 Graham sample ballot); the only root-level 'official canvass.pdf' is the May 10 2014 canvass. Commissioners Court page (young.CommCourt) and minute-order page carry no agendas or packets for 2024 (only precinct maps, rules of procedure and a FY2021 minute-order PDF); the County Clerk page lists only a 2026 trustee-sale notice, so no 11/12 or 11/25/2024 packet exists online. 16 more guessed canvass/precinct filenames under /upload/page/2681/2024/ returned 404. The 'results.texas-election.com' link on the elections page is the Texas SOS statewide ENR site (county totals, no precincts). Graham Leader coverage returned HTTP 429. Still not found.

### Zapata County

Page checked: https://www.co.zapata.tx.us/page/zapata.elections

What is online (not precinct level):
- `November 5 2024 General and ZCISD - unofficial results.pdf` — https://newtools.cira.state.tx.us/upload/page/6427/docs/Results/November 5 2024 General and ZCISD - unofficial results.pdf  
  fetched 2026-11-04; SHA-256 `19a05c0b7276b6895edd1f9e28834248cc2f275a7516574d2185b1afa7216bd5`; pdf scanned; Hart-style cumulative results, Zapata County General Election 11/5/2024, 7 pages, image-only scan (OCR works). UNOFFICIAL, COUNTYWIDE TOTALS ONLY; absentee/early/election-day split; President and U.S. Senate present.; unofficial
- `2024 11 15 Minutes.pdf` — https://www.co.zapata.tx.us/upload/page/8469/docs/Minutes/2024/2024 11 15 Minutes.pdf  
  fetched 2026-11-04; SHA-256 `3c4e2166fad3df1a7fb2b7c3b1845e1fad00f6e8327cc58178c3699daa8951a3`; pdf text; Commissioners Court minutes 11/15/2024, 3 pages; 'Order approving to canvass election results from November 5, 2024, General Election' - no vote figures attached.; official
- `2024 11 12 Minutes.pdf` — https://www.co.zapata.tx.us/upload/page/8469/docs/Minutes/2024/2024 11 12 Minutes.pdf  
  fetched 2026-11-04; SHA-256 `905a906492ffb8ea0f82d6284f5aef6a8655d5435922eb767b65de50dac0a9ca`; pdf text; Commissioners Court minutes 11/12/2024, 5 pages; no election results.; official
- `2024 11 25 Minutes.pdf` — https://www.co.zapata.tx.us/upload/page/8469/docs/Minutes/2024/2024 11 25 Minutes.pdf  
  fetched 2026-11-04; SHA-256 `d7ea143160cdf38cf325ce5bbfe247caa831fc9521be561af7d80fd9077a7566`; pdf text; Commissioners Court minutes 11/25/2024, 6 pages; no election results.; official

Records request to: Zapata County Clerk (election administration); Mary Jayne Villarreal-Bonoan; 956-765-9915; 200 E. 7th Avenue, Ste. 138, Zapata, TX 78076

Notes: Elections page (co.zapata.tx.us = newtools.cira.state.tx.us/page/zapata.Elections) links only an UNOFFICIAL cumulative report for Nov 5 2024; no official/canvass report and no precinct report for this election (the county did post per-precinct PDFs for the March 2020 primary, so precinct reports exist in its system). Guessed filenames in /docs/Results/ for an official 2024 general report all returned 404. Canvass was ordered 11/15/2024 per minutes. Election-day polling places: Pct 1, 1A, 1B, 2, 2A, 3.

