# surfs_up
## Overview
During my vacation in Hawaii last year, I discovered a new passion for surfing and decided to move there. To make a living, I plan to open a Surf and Shake shop in Oahu, Hawaii. To fund my business, I reached out to an investor W.Avy who loves surfing. The investor seemed interested but was concerned about the weather. To help the investor decide, a weather dataset of Oahu was provided to perform analysis on weather patterns. 

To analyze the precipitation and weather station data, SQLite and SQLAlchemy were used. An app was then developed using Flask to show results from the analysis. Upon reviewing the analysis, W.Avy requested further analysis regarding the below:
- Temperature statistics for June in Oahu
- Temperature statistics for December in Oahu

## Results
### Temperature Statistics for June and December in Oahu
![image](https://user-images.githubusercontent.com/76491891/115936863-64d07500-a464-11eb-84ff-a615c92af0e3.png)   ![image](https://user-images.githubusercontent.com/76491891/115937217-58005100-a465-11eb-95f6-a11cdea0d1e5.png)

- The average temperature for June is 74.94 and December is 71.04, respectively. This shows a moderate temperature with a 3.9 average temperature difference for June and December in Oahu. 
- The maximum temperature for June is 85 and December is 83, respectively. There is no significant difference in maximum temperatures for June and December as there is only a 2-degree difference.
- The minimum temperature for June is 64 and December is 56, respectively. There is an 8-degree temperature difference which may cause a dip in sales during December.

## Summary
There are no significant average temperature differences for June and December in Oahu, which will make surfing and Ice creams desirable throughout the year. 

Below are additional ideas to gather weather data for June and December:
- An analysis of the precipitation data for June and December can be performed. December has the highest mean precipitation of 0.21 whereas June has the lowest mean precipitation of 0.13. This indicates a higher chance of rainfall during December.
![image](https://user-images.githubusercontent.com/76491891/115937058-e1635380-a464-11eb-9438-f8e5182e341b.png)   ![image](https://user-images.githubusercontent.com/76491891/115937075-eaecbb80-a464-11eb-81e4-a801fb03534b.png)

- A histogram is used to visualize the trend of temperature analysis for Oahu during June and December. By grouping the data into 15 bins, a histogram can be plotted to show the frequency of temperature patterns. 
![image](https://user-images.githubusercontent.com/76491891/115937114-06f05d00-a465-11eb-8991-9fb652b6ddd5.png)
![image](https://user-images.githubusercontent.com/76491891/115937128-11aaf200-a465-11eb-8bcc-99f7a459b4ef.png)
