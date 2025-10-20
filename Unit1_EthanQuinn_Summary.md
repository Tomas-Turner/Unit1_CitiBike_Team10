## Summary  
For this project, I analyzed the NYC Citi Bike dataset using BigQuery and Gemini to find key patterns in trip duration, station activity, and time-of-day usage. My three main hypotheses focused on (1) how trip length differs between subscribers and customers, (2) which start stations are used the most, and (3) how trip counts vary by hour and day.  

## Findings  
1. **User Behavior:** Subscribers took much shorter trips on average (around 800 seconds) compared to casual users (about 2100 seconds). Subscribers mainly use bikes for quick commutes, while casual riders take longer trips or one-offs.  
2. **Busy Stations:** Pershing Square North, E 17th & Broadway, and W 21st & 6th Ave were the top three starting stations, showing high demand in certain areas that likely need more bikes available.  
3. **Rush Hour Trends:** Weekday usage clearly peaks during morning and evening rush hours, showing that Citi Bike is mostly used for commuting.  

## Validation Changes  
While validating, I had to fix small issues like extra rows, missing filters for nulls, and datatype mismatches in the heatmap. Cleaning these up made the results more consistent and the visuals clearer.  

## Recommendations  
1. **Redistribute Bikes:** Add more bikes to the top stations during rush hours to handle higher demand.  
2. **Adjust Pricing:** Offer small incentives for subscribers to ride during off-peak hours to help balance usage.  

## Reflection  
Using Gemini made hypothesis generation and SQL debugging much faster. Combining that with BigQuery helped dig into trends that point to real operational changes NYC DOT could make to improve bike availability and user experience.  
