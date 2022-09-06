# Bike Share Analysis with Ford GoBike Data 
## by Abdulahi Adedayo

## Dataset fordgobike-tripdata

This project used the Ford GoBike's trip data available in their [website](https://www.fordgobike.com/system-data).

I downloaded the trip data, read it into pandas, the compiled data contained 1,863,721 rows and 16 columns and i did some wranggling on the data, then i did some visualizaions using important columns like:

- Trip Duration (seconds)
- Start Time and Date
- Start Station ID
- Start Station Name
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Member Year of Birth
- Member Gender
- Age
- Day

## Prerequisites

Before running the codes, you will need to install these:

- Anaconda
- Python (Minimum 3.7)
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Python Notebook and Scripts

fordgobike-tripdata.ipynb - Main project file, a IPython Notebook that contains the analysis for the project.
fordgobike-tripdata2.ipynb - This IPython Notebook contains starter cells to help organize the slide deck deliverable.

## Summary of Findings

The average trip duration that the users took was around 5 to 15 minutes.

89.2% of the total trips were taken by Subscribers, which are members of the GoBike program.

Also, the age group with the most trips was between 30-35 years old.

The Customers users (casual users) usually took more time in their rides than Subscribers.

## Key Insights for Presentation

For the presentation, I display the influence of variables in question (season of year, user type, user age and gender) on the Users' GoBike trip duration. I start by introducing the duration variable and followed by the main variable in question, season.

Afterwards, I introduce each of the relationship one by one. To start, I use the bar plots of duration and season to show that Summer season does have the longest trip duration. Then, I do violin plots of duration and user type. I'm only looking at
the trip duration of less than 60 minutes here, to focus the analysis. The other two variables, age and gender, are covered afterwards, using bar plots. I've made sure to use different color for each age group to make sure it is clear that they're different between bars.