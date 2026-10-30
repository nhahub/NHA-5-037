# Sleep Quality & Lifestyle Analysis – DEPI Graduation Project

## Project summary
A Data Analysis project exploring sleep duration, sleep-stage percentages, sleep latency, sleep debt, and next-day fatigue alongside lifestyle indicators such as bedtime phone use, evening caffeine, physical activity, and chronotype.

## Tools
- Microsoft Power BI Desktop (Power Query, data model, DAX, report pages)
- Microsoft Excel (supporting analysis and validation)
- GitHub repository supplied by the DEPI training company

## Repository structure
- `01_Project_Planning/` – proposal, plan, roles, risks, KPIs
- `02_Requirements/` – stakeholders, user stories, functional and non-functional requirements
- `03_System_Analysis_Design/` – conceptual diagrams, architecture, wireframe
- `04_Data_Documentation/` – data dictionary and cleaning log
- `05_Power_BI/` – the Power BI file supplied for this update

## Important data-quality decision
The Power Query script currently removes duplicates using `user_id`. Confirm the dataset grain before retaining this step. If multiple rows per user are valid observations, deduplicating by user_id will discard valid records. Preserve the original raw CSV and document the final decision.

## How to open
1. Install a compatible version of Power BI Desktop.
2. Open the `.pbix` file.
3. If the query points to a local CSV path, update the `FilePath` parameter/source step to the location of the raw CSV.
4. Select Refresh and review Power Query errors and data-quality profiles.

## Notes
This package contains draft project documentation based on the supplied dataset schema and the current project description. Replace all `[Name]` placeholders, verify the proposed data model against the actual PBIX, and obtain instructor feedback before marking the documents final. The analysis is descriptive and does not establish causation or provide medical advice.


## Flexible planning decisions
- Individual task ownership is not assigned in this draft; work areas are described as shared team responsibilities. Names can be added later if requested by the instructor.
- The final dashboard page count is intentionally open. Content areas may be combined, split, or reordered after analysis and review.


PROJECT TEAM
Project Leader: Abdelrahman Ahmed Mohamed
Instructor: Nouran Tarek El Zeky
Team Members:
- Habiba Hossam Hussein
- Toka Sami Mohamed
- Jana Waleed Mohamed
- Tarek Mohamed Anwar
- Youssef Mohamed Ibrahim


## Power BI file used in this package
The PBIX in `05_Power_BI/` is the file supplied separately as `Final Project v1.pbix`. The remaining documentation and supporting artifacts have been retained from the original package because the supplied PBIX model diagram identifies the same sleep/lifestyle subject area (including sleep data, age/gender, caffeine, bedtime phone/app use, and related factors). Open the PBIX in Power BI Desktop and verify the report page and visuals before final submission.
