# How to get more to sit the SAT?

The college admissions tests landscape is fiercely competitive between the SAT and ACT. This project uses data from the 2017 and 2018 SAT and ACT tests across the US states to derive insights into participation rates through student performance visualization and statistical inferences.

It will also form opinions on the reasons for state participation in college admissions tests and give recommendations on driving SAT participation in specific states.

## Problem Statement

Based on changes in state SAT and ACT participation rates and performance, which states should be targeted to raise SAT participation rates?

## Structure

- 2017 Data Import & Cleaning
  - The project begins with data preparation of 2017 participation and test scores.
- 2018 Data Import and Cleaning
  - 2018 data is manually extracted and cleaned using the same process.
- [Data Dictionary for All Data Used](#Data-Dictionary-for-All-Data-Used)
  - Data dictionary of final data to be analyzed.
- Exploratory Data Analysis
  - Summary statistics and brief descriptions of data groups, including maximum and minimum comparisons.
- Data Visualization
  - Histograms, scatter plots, and box plots to discover data trends.
- Descriptive and Inferential Statistics
  - Summarizing distribution of data and apply statistical inference where appropriate.
- Outside Research
  - Identifying promising trends and researching possible underlying reasons.
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)
  - Key takeaways and recommendations on how to leverage these insights for higher participation.

## Data Dictionary for All Data Used

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|2017 SAT|US state where SAT data comes from, including DC.|
|2017_sat_participation|float|2017 SAT|Participation rate in SAT within state.|
|2017_sat_read_write|int|2017 SAT|Evidence-based Reading and Writing section of SAT, with score between 200 and 800.|
|2017_sat_math|int|2017 SAT|Math section of SAT, with score between 200 and 800.|
|2017_sat_total|int|2017 SAT|Total score of SAT, combining EBRW and Math sections, for total score between 400 and 1600.|
|2017_act_participation|float|2017 ACT|Participation rate in ACT within state.|
|2017_act_english|float|2017 ACT|English section of ACT, with score between 1 and 36.|
|2017_act_math|float|2017 ACT|Math section of ACT, with score between 1 and 36.|
|2017_act_reading|float|2017 ACT|Reading section of ACT, with score between 1 and 36.|
|2017_act_science|float|2017 ACT|Science section of ACT, with score between 1 and 36.|
|2017_act_composite|float|2017 ACT|Composite score of ACT averaging scores from four subject sections, with score between 1 and 36.|
|2018_sat_participation|float|2018 SAT|Participation rate in SAT within state.|
|2018_sat_read_write|int|2018 SAT|Evidence-based Reading and Writing section of SAT, with score between 200 and 800.|
|2018_sat_math|int|2018 SAT|Math section of SAT, with score between 200 and 800.|
|2018_sat_total|int|2018 SAT|Total score of SAT, combining EBRW and Math sections, for total score between 400 and 1600.|
|2018_act_participation|float|2018 ACT|Participation rate in ACT within state.|
|2018_act_english|float|2018 ACT|English section of ACT, with score between 1 and 36.|
|2018_act_math|float|2018 ACT|Math section of ACT, with score between 1 and 36.|
|2018_act_reading|float|2018 ACT|Reading section of ACT, with score between 1 and 36.|
|2018_act_science|float|2018 ACT|Science section of ACT, with score between 1 and 36.|
|2018_act_composite|float|2018 ACT|Composite score of ACT averaging scores from four subject sections, with score between 1 and 36.|

## Conclusions and Recommendations

- State regulations have a large impact on SAT participation.
  - Target states that are due to review their college admissions provider.
  - Negotiate for school hours testing.
  - Include free testing.
  - Continue lobbying effort even after switch as legal challenges may arise.

- Conclusion
  - There are a handful of states that mandate either the SAT or ACT and have higher ACT participation at the moment. Ohio is the most populous among them and should be targeted for driving higher SAT participation since state rules already allow for it.
