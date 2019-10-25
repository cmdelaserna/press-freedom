# press-freedom
An index to monitor/forecast press freedom emergencies

### Protoype using data from African countries from the Armed Conflict Location & Event Data Project
https://www.acleddata.com/curated-data-files/

Data import
- Import excel file, add date column and export it as json
- Use json file for all future work
- Select columns to keep, rename column

Data preparation
- Encode event_type and sub_event_type for ML analysis
- Aggregate by month
- Function to get a dataset for a specific country
- Annotate data: create aggregate value for fatalities, other events?

ML
- Separate dataset into training, test, validate
