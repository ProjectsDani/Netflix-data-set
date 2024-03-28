# Netflix-data-set
Cleaning raw data set and importing it in Power Bi for analysis.


Steps of cleaning the Data:
- highlighted the cast column, directors, and listed in then did text to column formula(spilt a single column text into mulltiple coloumns) on the data tab, by choosing delimited, commma.
- used trim formula (=Trim(column number)) on the description, country, listed in, director, and cast columns. So i can remove unwanted black spaces from cells. Then seperated the columns to their own sheet
- When seperated the cast, directos, countries, description, and listed in, i had to make a relationship between the columns and unique show id.
- Then i selected all the data by ctrl,shift, end from the cast and the other seperated columns And  pasted them as values
- I seperated the duration column by using text to columns and created a new column called duration type, and i filtered out the data to see what i am dealing with.
-  used the unique formula (which acts like a distict) on the duration_type column and found out that some movies dosent have a duration time
-  any missing data that i found i used find and select fuction, and missing data will be shown as null.
  
