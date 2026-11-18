# LLM Output Comparator & RLHF Scoring Utility

A Python command-line tool built to ingest side-by-side (SxS) model outputs, apply structured evaluation rubrics, and generate comparative scorecards for LLM benchmarking[cite: 1, 2].

## Features
- **Side-by-Side Ingestion:** Parses JSONL evaluation files containing comparative model responses.
- **Rubric Grading:** Automates criteria-based scoring (instruction adherence, depth, formatting).
- **Tabular Export:** Aggregates findings and exports clean scorecards to CSV format using `pandas`[cite: 2].

## Tech Stack
- **Python** (Core parsing, File I/O)[cite: 2]
- **Pandas** (Tabular data aggregation)[cite: 2]

## Quick Start
1. Run the comparator tool:
   ```bash
   python comparator.py