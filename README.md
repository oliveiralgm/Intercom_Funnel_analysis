# Intercom Funnel Analysis

Python funnel analysis for Intercom lead-to-customer conversion. Portfolio exercise using pandas and matplotlib.

## What it does

- Loads funnel event data and cleans timestamps (including cases where invoice date precedes create date)
- Engineers lead-to-trial and trial-to-customer cycle times in days
- Breaks conversion by lead type, year/month cohorts, and related slices
- Prints frequency tables and plots for exploration (run from terminal; redirects output to a results file)

## Files

- `Funnel Analysis.py` — main analysis script
- `Intercom - Funnel Anlaysis.pdf` — written writeup / presentation

## How to run

```bash
python "Funnel Analysis.py" > MktFunnel.txt
```

Expects a tab-delimited `data.csv` next to the script (not checked in here).
