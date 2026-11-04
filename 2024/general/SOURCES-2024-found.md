# 2024 general election precinct sources, batch 1 (counties that already had a file)

Batch 1 covered the ten counties that already had a file in this directory:
Cochran, Hill, McMullen, Newton, Rains, Terrell, Webb, Wichita, Wilson, Yoakum.
No new precinct-level file was found for this batch; the notes below record
what was checked on 2026-11-04.

## Problems with existing files

### Rains (existing file is not a general election report)

`2024 Rains County, TX precinct-level results.csv` is a Hart export covering
only "Rains County Proposition A", a school trustee race, a mayor race and two
city council races. It has no President, U.S. Senate or other general election
contest and no precinct names. It cannot be used for the 2024 general.

Checked 2026-11-04:

- County elections page: https://newtools.cira.state.tx.us/page/rains.Elections
  lists only two November 5, 2024 documents, both *cumulative* (county-wide)
  reports with absentee / early / election day columns:
  - Official: https://newtools.cira.state.tx.us/upload/page/2858/November%205,%202024%20Presidential%20Election/Rains%20County%20Official%20Results%20November%205%202024.pdf
    (8 pages, scanned; "Cumulative Results Report", run 11/12/2024, "Polling Places Reporting 10 of 11")
  - Unofficial: https://newtools.cira.state.tx.us/upload/page/2858/November%205,%202024%20Presidential%20Election/UNOFFICIAL%20RESULTS%2011-5-24%20GENERAL%20ELECTION-RAINS%20CO.pdf
  Neither is precinct-level, so neither was saved here. The page does carry
  "Official Precinct by Precinct Results" for the 2026 primary, so the office
  can produce that report on request.
- Web search for a Rains canvass packet or precinct report: nothing found.

**Not found. Records request would go to:**
Lisa Kneifl, Elections Administrator, Rains County,
220 W Quitman St, Suite E, Emory, TX 75440.
Elections Department (903) 473-5009, office (903) 473-5027,
lisa.kneifl@rainscounty.gov.
Ask for the November 5, 2024 general election "Precinct by Precinct" report
(the Hart Verity report the county posted for the March 2026 primary).

### Cochran (existing file is an unofficial tally sheet with a column problem)

`2024 Cochran County, TX precinct-level results.pdf` is headed "NOVEMBER 5TH
GENERAL ELECTION TALLY SHEET - EARLY VOTING IN PERSON / UNOFFICIAL RESULTS"
with columns EV, BBM, BOX 101, 202, 303, 306, 404, TOTAL. In every contest the
EV column exceeds the EV ballots cast ("Number Voting" 495) and matches
EV + BBM, so the TOTAL column double-counts mail ballots (county totals run
about 5% above the Texas Legislative Council VTD data; subtracting BBM from
EV reproduces the TLC figures within 1 vote). The file was converted as
printed and the problem is listed in the data PR draft.

Checked 2026-11-04: the county site (https://www.co.cochran.tx.us/, pages
`cochran.Elections`, `cochran.Minutes`) links no results documents. A
corrected or official precinct report would have to be requested from the
Cochran County Clerk, Cochran County Courthouse, 100 N Main St, Morton, TX
79346, (806) 266-5508.

### Webb (scanned; a text version was looked for)

`2024 Webb County, TX precinct-level results.pdf` is an 88-page scanned
Electionware "PCT by PCT" table (unofficial, run 11/13/2024). The county's
agenda server (agenda.webbcountytx.gov:8085), which hosted the 2020, 2022 and
2023 canvass packets, refused connections from this environment on
2026-11-04, so the November 2024 canvass packet could not be checked for a
text-based precinct report. Worth one manual look by the owner:
https://agenda.webbcountytx.gov:8085/ (search the November 2024 meetings for
"Canvassing Document").

### McMullen (scanned, unlabeled precinct report)

`2024 McMullen County, TX precinct-level results.pdf` is five Electionware
"Summary Results Report" print-outs scanned duplex (blank backs): one early
voting report (absentee and early voting columns, county-wide) and four
election-day reports, one per precinct. The precinct is written by hand on
the first page of each report ("EV", "Pct 1", "Pct 2", blank, "Pct 4"); the
unlabeled report was taken as Pct 3 because it is the only election-day
report that carries the County Commissioner Pct 3 contest.
