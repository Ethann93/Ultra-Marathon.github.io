# Exploratory Data Analysis (EDA) on Ultra Marathon Races

In this README, we perform EDA on a dataset of ultra marathon races using Python and libraries like pandas, numpy, seaborn, and matplotlib. 

## Key Steps

**Data Loading:** We start by loading the dataset using pandas.

**Data Exploration:** We explore the dataset's basic information, such as its dimensions and data types. Summary statistics are also generated to understand the data.

**Data Analysis:** Key analyses include counting event distances, analyzing athlete countries, and checking for UK-based athletes.

**Data Cleaning:** Data cleaning steps involve selecting specific race distances, focusing on events in the USA during 2022, and performing various data cleaning tasks like handling dates, age, and performance.

**Data Visualization:** We create various visualizations to answer specific questions, such as:

1) Histograms of race lengths.

![output](https://github.com/Ethann93/Ultra-Marathon/assets/133777296/ba92fec6-0e17-4f37-b500-40aa831d3198)

2) Distribution of athlete average speed in 50-mile runs.

![Distribution of Athlete Average Speed in 50 Mile Run](https://github.com/Ethann93/Ultra-Marathon/assets/133777296/2c7f8a1c-ebbd-42db-95d1-b5a23b9e2b59)


3) Analysis of average speeds by age groups in different race lengths.

4) Analysis of the impact of the season on athlete speeds.

**Data Export:** Finally, the cleaned and processed data is exported to a CSV file for further analysis or reporting.

## Key Questions and Visualizations

**Difference in Speed of Males & Females:** We visualize and compare the speed of male and female athletes in 50km, 50mi, and 100mi races.

**Fastest and Slowest Age Groups in 50-mile Races:** We identify the age groups with the highest and lowest average speeds in 50-mile races.

**Fastest and Slowest Age Groups in 50km Races:** Similar to the previous question, but for 50km races.

**Fastest and Slowest Age Groups in 100-mile Races:** Similar to the previous question, but for 100-mile races.

**Impact of Season on Athlete Speed: We analyze the effect of the season (spring, summer, fall, or winter) on athlete speeds.**

## Data Export

The final cleaned and processed dataset is exported to a CSV file named 'USA_Events_2022.csv' for further analysis or reporting.

## Data Source

The data for this dashboard is sourced from https://www.kaggle.com/code/rizzle/exploring-ultra-marathon-dataset
