# press-freedom
An index to monitor/forecast press freedom emergencies

### Protoype using data from African countries from the Armed Conflict Location & Event Data Project
https://www.acleddata.com/curated-data-files/

Data import
- Import excel file.
- Add date column. 
- Export it as json
- Use json file for all future work

Data transformations
- Select columns to keep, rename columns
- Encode categorical data for ML analysis
- Function: return a dataset with data only from a specific country

ML - 
- Goal: to classify data every month by buckets, according to risk profile
- Use this classification to predict risk for current month
- Separate dataset into training, test, validate

Ideas:
- Create aggregated value for fatalities, other events?
