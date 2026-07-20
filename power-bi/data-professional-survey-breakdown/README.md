# Data Professional Survey Breakdown

A guided Power BI build following Alex The Analyst's data professional survey
project ([YouTube](https://www.youtube.com/watch?v=pixlHHe_lNQ&list=PLUaB-1hjhk8HqnmK0gQhfmIdCbxwoAoys&index=9)).
The survey was designed and collected by the tutorial's author, who asked the
questions and gathered the responses; I followed his build to practice Power BI's
data cleaning, modeling, and visualization tooling. The design and choice of visuals
follow the tutorial rather than my own judgment.

## Dataset

Responses to a survey of data professionals, covering role, whether they switched
careers into data, salary band, industry, favorite programming language,
satisfaction across six workplace dimensions (salary, work/life balance, coworkers,
management, upward mobility, learning), perceived difficulty of breaking into the
field, age, country, and demographics.

## What I practiced

- **Splitting columns by delimiter** in the Power Query transform step, separating
  combined values into clean fields (for example, salary bands entered as
  `106k-125k`, and free-text answers stored as `Other (Please Specify):<value>`).
- **Customizing color palettes** to control the dashboard's visual theme rather
  than relying on defaults.
- **Configuring gauge visuals**, including setting minimum and maximum bounds to
  frame the happiness scores on a fixed scale.
- **Building and configuring a treemap** to show the distribution of participants
  by country.
- **Setting up stacked bar charts** to break a categorical measure down by a
  second category (programming language by job title).
- **Aggregating with built-in summarization** (using the field dropdown to switch
  measures to averages) for salary and age, rather than writing custom DAX.
- **Enabling slicer and cross-filter interactions** so selecting one visual filters
  the others across the report.

## Notes

This is guided work, so some design choices reflect the tutorial rather than what I
would choose independently. As my own design judgment develops, some of these
visuals (for example, the gauges and the donut) are ones I would reconsider in a
later redesign.
