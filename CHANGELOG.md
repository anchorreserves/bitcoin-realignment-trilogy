# Changelog – The Realignment Trilogy

All notable changes to the Realignment Trilogy and its quarterly empirical appendix.

## [Unreleased] – Next Quarterly Update (15 December 2026)
- Add Q4 2026 empirical results to `appendix-quarterly-empirical-log.md` and the Excel log
- Papers remain unchanged unless the author explicitly revises them

## [v1.3] – 29 September 2026 (Q3 2026 empirical refresh)
Empirical files only. The three papers (markdown and PDF) are unchanged. Published to GitHub main (merged via PR #2, 2026-09-29, commit 5e4f3f68) and Zenodo (DOI 10.5281/zenodo.23047828, published 2026-09-29).

- Added Q3 2026 (log date 15 September 2026) observation row across Dashboard, A.1–A.4, Schedule
  - US M2 updated to **$23.34 T** (FRED `M2SL` Aug 2026 = 23,342.8; retrieved 2026-09-29 America/Chicago)
  - Fed balance-sheet % of GDP for the **new Q3 row only** = **20.7**, using Methods recipe `(WALCL in billions)/GDP × 100` with last Wednesday WALCL in 2026:Q2 = 2026-06-24 (6,735,645 $M) and GDP 2026:Q2 = 32,486.066. Historical BS%GDP cells including Q2 21.8 **not rewritten**
  - Broad-money multiplier stores qualitative **elastic** only (FRED `MULT` discontinued). Methods candidate `M2SL/BOGMBASE` Aug 2026 ≈ 4.31 documented only — not a silent replacement for the historical numeric path
  - Top 1 % = **32.5** (Fed DFA / FRED `WFRBST01134` 2026:Q2; vintage release **18 September 2026**). Historical A.2/A.4 top-1 % path refreshed to the same vintage (30.2 in 2023:Q4 → 32.5 in 2026:Q2); A.2 and A.4 remain matched on every date. Concentration has **not** narrowed
  - BTC full-reserve lending **$85 B / 71 %**, global adoption **~8.8 %**, self-custody **50 %**, and K-divergence proxy **+4.0 %** carried with explicit **not-refreshed** notes (Glassnode Studio login required; Chainalysis 2026 Global Crypto Adoption Index of 23 Sep 2026 is country ranks without a global population %)
  - DeFiLlama free-API lending TVL ≈ $54.7 B recorded as cross-check only (not equated to Glassnode $85 B)
  - Wealth Gini 0.86 retained; still not a DFA field; gap flagged
- Realignment Index remains **2.0** (all four tests Transitional). Schedule ~9 % adoption milestone **unassessable** without a primary adoption refresh
- Regenerated `appendix-quarterly-empirical-log.md` from the Q3 Excel
- Workbook Methods/CHANGELOG sheets updated; Dashboard sparklines restored from John’s 2026-08-24 sparkline source and extended to A.4 rows through Q3 (`C2:C12` / `D2:D12` on K24/L24)
- Excel filename recommendation: `Realignment_Trilogy_Quarterly_Log_Q3_2026.xlsx` (replaces in-repo `…_Q2_2026_Updated.xlsx` on publish)

## [v1.2] – 28 August 2026 (Q2 2026 Fed-aligned empirical correction)
Empirical files only. The three papers (markdown and PDF) are unchanged.

- Replaced the Q2 2026 Excel master with a Fed-aligned revision
  - Top 1% wealth share now uses Fed DFA net-worth share (FRED `WFRBST01134`), vintage 18 June 2026
  - Log-date to DFA-quarter map: 15 Mar → prior-year Q4; 15 Jun → Q1; 15 Sep → Q2; 15 Dec → Q3
  - A.2 and A.4 now match on every date (removed the 15 Dec 2025 32.1 vs 31.8 split)
  - Q2 2026 (15 June) top 1% revised from 31.2 to 31.6 (2026:Q1)
  - Historical top 1% path now follows the official series (30.3 in 2023:Q4 to 31.6 in 2026:Q1)
  - Added Methods sheet (multiplier 3.3, Fed balance-sheet % of GDP 21.8, and $85 B / 71% lending are documented; stored figures retained where the official recipe could not be reconstructed)
  - Added workbook CHANGELOG sheet; Gini flagged as not a DFA field
  - Dashboard A.4 wording corrected: official concentration has not narrowed over the logged window
  - Schedule Q3 2027 review date corrected from 2026-09-15 to 2027-09-15
- Regenerated `appendix-quarterly-empirical-log.md` from that Excel
  - Version line: Fed-aligned revision of the 15 June 2026 entry (not a Q3 update)
  - Realignment Index remains 2.0; all four tests remain Transitional
- `hashes.txt` to be refreshed only for the empirical files that change

## [v1.1] – 15 June 2026 (Q2 2026 Quarterly Refresh)
- Updated living appendix `appendix-quarterly-empirical-log.md` with complete Q2 2026 data from the Excel log
  - Current Version set to Q2 2026 – 15 June 2026
  - Dashboard statuses, A.1–A.4 test logs, Realignment Index, and Resources refreshed
  - Schedule & Milestones: Q2 2026 status changed to Complete with full notes
- Supporting Q2 files (Excel log and Dashboard PDF) already present from the 15 June commit

## [v1.0] – 25 April 2026 (Initial Open Release)
- Full open-access PDFs and Markdown versions of all three papers
- Living quarterly empirical appendix created
- GitHub repository launched for maximum AI and search visibility

## Earlier versions
- March 2026: Original SSRN preprints (Abstracts #6332700, #6355099, #6368619)
