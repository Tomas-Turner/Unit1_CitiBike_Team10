## Team 10 – Prompt Log  

---

### Prompt 1 – Generate SQL for Hypothesis A  
**Where Used:** Hypothesis A (Trip Duration by User Type)  
**Prompt Summary:** “Write SQL to calculate the average trip duration by user type.”  
**What Happened:** The initial code ran correctly but included some null values.  
**Refinement:** Added a simple filter to exclude nulls in the `usertype` and `tripduration` columns.  
**Result:** Final query returned clean averages showing that subscribers take shorter rides than casual users.  

---

### Prompt 2 – Query for Busiest Starting Stations  
**Where Used:** Hypothesis B (Top Starting Stations)  
**Prompt Summary:** “Find the top 3 starting stations with the highest number of total trips.”  
**What Happened:** The first query displayed extra stations because the sorting order wasn’t limited properly.    
**Refinement:** Added a `LIMIT 3` clause and rechecked the descending order to show only the top results.   
**Result:** Pershing Square North, E 17th & Broadway, and W 21st & 6th Ave were confirmed as the busiest stations.  

---

### Prompt 3 – Create Heatmap by Hour and Day  
**Where Used:** Hypothesis C (Trips by Hour and Day of Week)  
**Prompt Summary:** “Generate SQL and Python code to create a heatmap of trips by hour and weekday.”  
**What Happened:** The visualization initially failed because trip counts were still read as floats.  
**Refinement:** Converted total trip counts to integers before plotting.  
**Result:** The heatmap displayed clearly, showing strong weekday commuting peaks during morning and evening hours.  

