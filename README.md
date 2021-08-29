# Forecast Proportion of West Java Society Staying Put at Home During COVID-19 Pandemic

by Suwarti

# Use Case

- Use Case Summary
- Objective Statement:
  * During the COVID-19 pandemic Facebook released data on 'Movement Range Maps’. Data contains two main information, there are data on changes in movements of society and proportion of society staying put at home. 
  * This case has some Objective Statement based on the data:
   * Build model to forecast proportion of West Java society staying put at home in the next 2 weeks.
   * Recommendation to treat West Java society based on forecasting model.

- Challenges:
  * Large size of data, can not maintain by excel spreadsheet.
  * Need several coordination from each department.

- Methodology / Analytic Technique:
  * Descriptive analysis
  * Graph analysis
  * Machine learning model

- Business Benefit:
  * Get behaviour data from proportion of West Java society staying put at home.
  * Know how to treat West Java society based on forecasting model.

- Expected Outcome:
  * Machine learning model that forecast proportion of West Java society staying put at home in the next 2 weeks.
  * Recommendation to treat West Java society based on forecasting model.
  
 # Business Understanding

- During the COVID-19 pandemic Facebook released data on 'Movement Range Maps’. Data contains two main information, there are data on changes in movements of society and proportion of society stay at home. 
- This case has some Objective Statement using the data:
 * Build model to forecast proportion of West Java society staying put at home in the next 2 weeks.
 * Recommendation to treat West Java society based on forecasting model.
 
# Data Understanding

- Source Data: https://data.humdata.org/dataset/movement-range-maps
- These data sets are intended to inform researchers and public health experts about how populations are responding to physical distancing measures. In particular, there are two metrics, Change in Movement and Stay Put, that provide a slightly different perspective on movement trends. Change in Movement looks at how much people are moving around and compares it with a baseline period that predates most social distancing measures, while Stay Put looks at the fraction of the population that appear to stay within a small area during an entire day.
- Data of Movement Range Maps from 01 March 2020 to 31 December 2020.
- The dataset has 9 columns and 5,229,342 rows.
- Data is provided in one global tab-delimited text file. 	

- Data Dictionary:
  * ds: Date stamp for movement range data row in YYYY-MM-DD form
  * country: Three-character ISO-3166 country code
  * polygon_source: Source of region polygon, either “FIPS” for U.S. data or “GADM” for global data
  * polygon_id: Unique identifier for region polygon, either numeric string for U.S. FIPS codes or alphanumeric string for GADM regions
  * polygon_name: Region name
  * all_day_bing_tiles_visited_relative_change: Positive or negative change in movement relative to baseline
  * all_day_ratio_single_tile_users: Positive proportion of users staying put within a single location
  * baseline_name: When baseline movement was calculated pre-COVID-19
  * baseline_type: How baseline movement was calculated pre-COVID-19



