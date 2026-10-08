# V&A Museum Business Intelligence Dashboard (Excel & Power Pivot) – Group Project

## Tools & Skills
- **Tools:** Microsoft Excel – Power Query, Power Pivot data model, PivotTables, PivotCharts and slicers
- **Data modelling:** Snowflake schema with helper dimension tables (date, visitor type, category and museum)
- **Data cleaning:** Excel functions (PROPER, ABS, TRIM, CLEAN) and data validation rules
- **Skills:** BI requirements, data dictionaries, sentiment and thematic analysis, dashboard design, stakeholder recommendations, team collaboration

## What I Did
This was a group project (5 members) for the Business Intelligence module of my Data Analytics MSc. We built a BI dashboard for the Victoria and Albert Museum (V&A) using 2023–2024 data on exhibitions and events, museum visits, gift shop sales, donations and visitor feedback. The dashboard has a tab for each board role, with each tab's analysis tied to the V&A's five strategic missions.

- **Data cleaning:** I cleaned the Exhibitions & Events dataset, which became the central table of the data model, in 12 documented steps. These included removing a duplicate event, correcting negative attendance values, fixing date formats and typos, recalculating revenue as attendance × ticket price, stripping hidden characters, and adding validation rules and dropdowns.
- **Requirements & documentation:** I wrote the BI requirements (purpose, users, goals, objectives and hypotheses), the data dictionary for all five datasets and the strategic questions each dataset could answer.
- **Feedback analysis:** I coded broad themes in visitor feedback comments to support the team's sentiment analysis of 3,138 comments.
- **Finance dashboard:** I analysed the data for the Finance dashboard and wrote the finance recommendations and the ethics section for the Events data.
- **Team:** We integrated the five datasets in a Power Pivot data model and built dashboards for the COO, Fundraising, Commercial, Finance, Learning & Young V&A, and National Programmes sentiment.

## Key Findings
- Donations were the largest income stream, well ahead of retail and ticket sales. This shows strong support for the museum but also a reliance on a single income source.
- Event income peaked in Q1 and then declined. Retail and donations peaked in January, and donations surged in December, so income depends heavily on the winter months.
- Student-targeted events generated over two-thirds of ticket revenue. Japan: Myths to Manga was the highest-earning exhibition.
- Physical visitors gave more through round-up donations at the till, while virtual visitors gave more through direct donations.
- Revenue and attendance had a weak negative relationship: the highest-earning events had moderate rather than peak attendance. We therefore recommended value-driven programming and pricing over chasing visitor numbers.

## Files
| File | Description |
|------|-------------|
| `Group 2 Report.pdf` | Full group report: BI requirements, data preparation, dashboard design, analysis, ethics and recommendations |
| `V&A Dashboard – Group 2.xlsx` | The interactive Excel dashboard with the integrated data model, pivot tables and a dashboard for each board role |
| `Events_KateForshaw.xlsx` | My cleaned Exhibitions & Events dataset, with a sheet documenting each cleaning step |
