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
- Rename columns
- Encode categorical data for ML analysis
- Function for basic visualization: plot data from a specific country

K-Clustering
- Tested k-clustering for all countries at once (2010 - 2019). Lacks specificity. 
- Next step: cluster date from one country. 
- Create function to cluster data independently from one coutry at once?