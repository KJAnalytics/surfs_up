# Surfs_up
Weather analysis for Oahu using python, jupyter notebook, and FLASK

##Overview
The focus of this project involves analysis of weather data(Temperatures) for Ohau, HI. A potential investor is considering opening a surf and ice cream shop.  His major concern is the temperature variations from summer to winter conditions and if the temperature can support a year round business.  The months of December and June   have been selected as representative for the Summer and Winter condition states.  

## Resources
- An sqlite database hawaii.sqlite.  
  - Database covers the period of 2010=2017 for Ohau.
    - extracted from the data base are the months of December (1517 rows of data) and June (1700 rows of data)
- Python version 3.9.13 with Jupyter Notebook and Flask utilized
- SQLite version 3.39

## Results and Analysis
Based on the analysis completed.  The investment of a year round surf shop is a reasonable risk considering average year round temperatures alone. With a 74 to 71 average temperature swing is modest and indicates a significant overlap in temperature ranges between Summer and Winter conditions.  Comparing the distributions of temperature per analysis month, even in December, the majority of the days are greaterh than 69 degrees reducing the risk of the extreme cold conditions.

Comparison of the data between the months include the following factors:
- For the month of June temperatures average 74.8 degrees with a range of 64-85.  When the standard deviation and 3-sigma is added that indicates that temperatures would naturally 64.8-84.3 degrees.
https://github.com/KJAnalytics/surfs_up/blob/main/Resources/June_temp_stats.png
https://github.com/KJAnalytics/surfs_up/blob/main/Resources/June_histogram.png
-For the month of December - temperatures average 71 degrees and range from 56-83.  When the standard deviation and 3 sigma is applied potential temperatures should fall between 60.2-82.3 degrees.
https://github.com/KJAnalytics/surfs_up/blob/main/Resources/Dec_temp_stats.png
https://github.com/KJAnalytics/surfs_up/blob/main/Resources/Dec_histogram.png

