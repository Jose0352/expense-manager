# Expense Manager
A simple command-line expense manager built with Python.

A scalable, automated personal finance tracker built to eliminate manual expense logging and financial blind spots.

## Context & The Problem

## Tech Stack

* **Language:** Python
* **Database:** SQL (engine to be decided)
* **Future Cloud Architecture:** AWS (Lambda, Amazon Bedrock)

* ## Roadmap
- [ ] **Phase 1: The Foundation.** Python script to parse and sanitize bank statements (CSV/Excel), storing transactions in a structured local SQL database.

## Problem Statement & Motivation
After relying on manual expense tracking for over 2 years, severe friction points emerged:
* **Human Error:** High frequency of forgotten dates, miscalculated amounts, and insufficient context per transaction.
* **Cognitive Load:** Overthinking small entries and feeling overwhelmed by manual data entry (including screenshots and physical receipts).
* **Inconvenience:** Time-consuming entry process leading to eventual abandonment of tracking.

This project addresses these exact pain points by automating the ingestion, processing, and storage of financial transactions.

## High-Level Architecture
1. **Data Ingestion (Input):** Accepts bank statement extracts (CSV/Excel) and email transaction receipts.
2. **Processing Engine:** Cleans, normalizes, and calculates expense totals/categories.
3. **Data Persistence (Storage):** Stores structured financial data into a database for historical analysis.
- [ ] **Phase 2: Cloud Automation.** Migrate processing to AWS Lambda to automatically ingest and parse email receipts and bank notifications.
- [ ] **Phase 3: AI Categorization.** Implement Amazon Bedrock to analyze ambiguous transaction text and automatically assign them to predefined budget categories.

- [ ] ## Setup & Usage
*(Instructions on how to run the project will be added as the codebase grows).*
