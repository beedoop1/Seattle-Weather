# Seattle-Weather

## Title: Project 1 (Rainfall Comparison)

### Description: Comparing rainfall between Seattle and New York

Data: The data was obtained by the National Centers for Environmental Information (NOAA). They provide many environmental precipitation, but we will be using the data of daily precipitation provided by the NOAA.

Link to Seattle Summary: https://www.ncei.noaa.gov/cdo-web/datasets/GHCND/locations/CITY:US530018/detail

Link to New York Summary: https://www.ncei.noaa.gov/cdo-web/datasets/GHCND/locations/CITY:US360019/detail

### Preparation of Data:
There were a few steps taken to prepare the data. Firstly, the data type for the date variable was converted for both datasets. Then irrelevant variables were removed from the dataset. After removing the irrelevant variables, one station from both datasets was chosen to be compared to each other. Duplicate values were removed, and both datasets were joined showing only the date, city, and precipitation for each city. Then two extra columns were added to the dataset to be used to analyze our data. Finally, all rows with missing data were dropped.

### File that performs data preparation: 
https://colab.research.google.com/drive/1PwJb2lMNpNRlJo-cbbiNSo29v7vMJd1N?usp=sharing

### Clean data file:
clean_seattle_nyc_weather.csv

### Analyzing the Data:
The steps taken to analyze the data were to first create a separate column for the year so we can easily get the data for the years used in the Colab notebook. Two different dataframes were made one in 2022 and one in 2023 because these two years were more recent than the data from 2020 which may prove more irrelevant now. Then multiple plots were made so we can see to compare the precipitation between both cities. Many analyzed plots were also scrapped as I believe the ones left in the notebook were all we needed to draw a final conclusion.
