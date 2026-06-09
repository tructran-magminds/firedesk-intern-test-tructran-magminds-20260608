# Firedesk Intern Test: tructran-magminds

**Namespace:** `firedesk-intern-test-tructran-magminds-20260608`

## Project Description
This repository serves as a realistic first-user validation environment for the Firedesk local developer setup. It is designed to test Composio credential configuration, GitHub and Google Workspace connector installation flows, and the Firedesk orchestrator's behavior across multiple data sources.

## Expected Orchestrator Task
The Firedesk orchestrator should be instructed to:
1. Connect to this GitHub repository and read the provided CSV datasets (`data/customer_feedback.csv` and `data/pipeline.csv`) and markdown documentation (`docs/release_notes.md`).
2. Read and cross-reference connected Google Workspace assets (Sheets, Docs, or PDFs) within the designated namespace.
3. Analyze the datasets against the release notes to identify logical discrepancies and data-quality issues.
4. Answer the specific analytical queries listed in `docs/open_questions.md`.
5. Output the results, explicitly noting any connector setup friction, read/write gaps, or timeout issues encountered during execution.
