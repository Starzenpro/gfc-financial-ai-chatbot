# GFC Financial AI Chatbot

## Overview

This project is part of my work with the Boston Consulting Group (BCG) GenAI Consulting Team. The goal is to build an AI-powered chatbot for Global Finance Corp. (GFC) to analyze and summarize key financial data from 10-K reports, enabling faster, more accessible insights into corporate financial performance.

## Project Objectives

- **Extract** key financial data (Total Revenue, Net Income, Total Assets, Total Liabilities, Cash Flow from Operating Activities) from the 10-K filings of Microsoft, Tesla, and Apple for the last three fiscal years.
- **Analyze** trends and key financial indicators using Python (pandas) in a Jupyter Notebook.
- **Document** findings and methodologies in a clear, narrative format.
- **Lay the foundation** for an AI-powered financial chatbot that leverages GenAI and NLP to provide user-friendly financial insights.

## Structure

- `notebooks/GFC_Financial_Analysis.ipynb`: Main notebook for data analysis and reporting.
- `requirements.txt`: Python dependencies.
- `.gitignore`: Standard ignores for Python and Jupyter projects.
- `.github/workflows/export-notebooks.yml`: GitHub Actions workflow to auto-export notebooks as HTML.

## Instructions

1. **Extract Data:**
   - Download 10-K filings from the SEC’s EDGAR database for Microsoft, Tesla, and Apple.
   - Manually extract key figures for the last three fiscal years.
   - Compile into a CSV file and place it in the `notebooks/` directory.

2. **Analyze Data:**
   - Open `GFC_Financial_Analysis.ipynb`.
   - Run the notebook to analyze trends, calculate year-over-year changes, and summarize findings.

3. **Document & Present:**
   - Use Markdown cells in the notebook to explain methodology and highlight insights.
   - Export your notebook as PDF or HTML for sharing.

## Continuous Integration

Every push or pull request to the main branch will automatically export all notebooks in the `notebooks/` directory to HTML (see `.github/workflows/export-notebooks.yml`). The HTML files will be available as build artifacts in GitHub Actions.

## Future Work

- Integrate automated document parsing for 10-K reports.
- Develop the AI-powered chatbot using NLP and GenAI techniques.

---

**Author:** Starzenpro (Junior Data Scientist, BCG GenAI Consulting Team)