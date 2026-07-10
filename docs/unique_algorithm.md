# Unique Prototype Algorithm

## Algorithm

**KulisCausalStatisticsRankAgent** (`P107-Kulis-Statistics`)

## Professor Alignment

- Professor: Brian Kulis
- Research area: Machine learning, statistics, computer vision, metric learning
- Focus terms: statistics, computer vision, metric learning

## Core Mechanism

This prototype prioritizes distribution-shift failures with confidence-aware calibration penalties.

## Decision Rule

Rank seed cases by vision-specific priority score with Kulis-aligned focus term 'statistics'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `vision` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to Brian Kulis's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
