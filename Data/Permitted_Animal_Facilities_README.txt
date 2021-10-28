NC Animal Permit Locations - April 2020

Data downloaded from https://deq.nc.gov/cafo-map in Excel format. 
Converted to CSV (removing top two rows) by john.fay@duke.edu  (Oct 2020)
Rows with missing coordinate data removed by john.fay@duke.edu (Oct 2020)
 -> df.dropna(how='any',subset=['Location Lat Num','Location Long Num']).to_csv('../data/Permitted_Animal_Facilities.csv',index=False)