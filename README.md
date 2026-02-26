# Bitman Map – Unstructured Data Scraping Project

## Overview

This project demonstrates how unstructured HTML data from the BCIT website can be transformed into structured academic information.

The goal was to extract course metadata including:
- Course codes
- Prerequisites
- Learning outcomes
- Course relationships

The final output includes a structured dataset and a prerequisite dependency map.

---

## Why This Is Unstructured Data

BCIT course outline pages are HTML documents.  
They are not provided as structured datasets (e.g., CSV or database format).  

This project performs:

1. Web scraping
2. Text cleaning
3. Structured data extraction
4. Graph modeling of prerequisite relationships

---

## Data Pipeline

1. Download raw HTML pages
2. Parse relevant sections (prerequisites, learning outcomes)
3. Convert extracted data into a structured DataFrame
4. Export structured CSV
5. Generate prerequisite graph visualization

---

## Outputs

- `outlines_summary.csv` – Structured dataset
- `bitman_prereq_map.png` – Prerequisite dependency visualization
- `bitman_map.ipynb` – Complete analysis notebook

---

## AI Use Statement

AI assistance was used to:
- Help structure the data pipeline
- Draft initial scraping and parsing logic
- Improve code clarity and organization

All code was tested, modified, and verified manually to ensure correctness.

---

## Tools Used

- Python
- Requests
- BeautifulSoup
- Pandas
- NetworkX
- Matplotlib
