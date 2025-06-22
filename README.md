# Operation-Analytics-and-Investigating-Metric-Spike
As a Lead Data Analyst at a Microsoft-scale company, leverage advanced SQL to optimize operations by Analysing end-to-end workflows to resolve bottlenecks for support/ops teams.  Diagnose metric spikes - Investigate sudden KPI changes  for product/marketing teams.   

Problem:

* Limited visibility into end-to-end operations and unexplained metric spikes (e.g., sudden drops in engagement or throughput).
* Need to deliver daily, data-driven answers to cross-functional teams using complex, time-series and relational datasets.

Solution:

* Job Data Analysis:

  * Calculated jobs reviewed per hour for each day in November 2020.
  * Derived 7-day rolling average throughput and recommended its use over volatile daily rates.
  * Computed each language’s percentage share over the last 30 days.
  * Identified duplicate rows via GROUP BY…HAVING.

* Metric-Spike Investigation:

  * Measured weekly user engagement overall and broken out by device.
  * Tracked user growth trends over time.
  * Analyzed weekly retention by sign-up cohort.
  * Assessed email engagement from the email\_events table.
  * Provided SQL queries plus interpretation of any sudden metric changes.
