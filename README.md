# Lab: SQL-to-Python Cloud Notebook Workflow

Support operations analysis built with **Identify → Assemble → Execute → Verify**: SQL in SQLite, results loaded into pandas, a matplotlib chart, and verification checks. Run in **Google Colab** with the database stored in Google Drive.

**Question:** Which support ticket categories took the longest to resolve for tickets created in Q1 2026 (Jan 1 – Mar 31), and does any team or category need closer review?

**Finding:** API Integration tickets handled by Enterprise Support averaged 17.6 days (9 tickets, 6-day benchmark). One 75-day ticket inflates that average; without it the group still averages 10.4 days, above both the benchmark and Platform Support on the same category.

## Files
- `sql_modern_workflows_lab.ipynb`: the completed notebook, with outputs from a Colab "Restart session and run all"
- `support_operations.db`: SQLite database (tickets, ticket_categories, teams, and more)

## Running it
- **Google Colab:** upload `support_operations.db` to the top level of My Drive, open the notebook, and click Runtime → Run all. The notebook mounts Drive automatically.
- **Local Jupyter:** keep the database in the same folder as the notebook.
