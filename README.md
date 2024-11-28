# Data Visualization Project : Unemployment in America


## Introduction
Welcome to my data visualization project! This project focuses on visualizing unemployment rates across the United States from 1976 to the present. The dataset includes data for all US states, the District of Columbia, and major metropolitan divisions. This post will guide you through the steps taken, the challenges faced, and the final outcome of this project.
[Unemployment in America Per US State](https://github.com/justin-2028/Unemployment-in-America-Per-US-State/blob/main/Unemployment%20in%20America%20Per%20US%20State.csv)

## Project Overview
The goal of this project is to provide an interactive and insightful visualization of unemployment rates in America. The dataset, "Unemployment in America Per US State," tracks unemployment rates since 1976. The visualization aims to answer key questions such as:

How do unemployment rates compare across different states?
What are the trends in unemployment rates over time?
How do unemployment rates correlate with other economic indicators?
What is the distribution of unemployment rates across states?
Which states have high unemployment risk factors?

## Questions & Tasks

1. **Compare Unemployment Rates Across Different States:**

   - Visualize and compare the unemployment rates for each
     state to identify states with the highest and lowest
     unemployment rates.

2. **Analyze Trends in Unemployment Rates Over Time:**

   - Track how unemployment rates have changed over the
     years or months to identify trends or seasonal patterns
     in unemployment.

3. **Explore the Relationship Between Unemployment Rates and
   Economic Indicators:**

   - Investigate how unemployment rates correlate with other
     economic indicators such as GDP growth or inflation
     rates to understand the broader economic context.

4. **Examine the Distribution of Unemployment Rates:**

   - Create histograms or box plots to visualize the
     distribution of unemployment rates across states and
     identify any unusual patterns or outliers.

5. **Identify States with High Unemployment Risk Factors:**
   - Use the dataset to identify states with high
     unemployment rates and analyze potential factors
     contributing to their high unemployment levels.

## Steps Taken
1. Data Collection and Preparation
The first step involved loading and parsing the CSV dataset. This included cleaning the data, handling missing values, and transforming it into a format suitable for visualization.
<img width="974" alt="Screen Shot 2024-11-28 at 2 46 46 PM" src="https://github.com/user-attachments/assets/5fb4b0df-9f8d-4fdd-8e19-63921bbbe96b">

2. Sketching and Prototyping
Next, I created hand-drawn sketches of the visualizations I envisioned. These sketches helped in planning the layout and interactions of the final visualization. Here are a few examples:

<img width="660" alt="Screen Shot 2024-11-28 at 2 45 21 PM" src="https://github.com/user-attachments/assets/1916e21b-65b2-41a1-b393-b31d2a2860d7">


3. Building the Visualization
Using tools like D3.js and Tableau, I built the initial prototypes of the visualizations. These prototypes were iteratively refined based on feedback and testing.
<img width="998" alt="Screen Shot 2024-11-28 at 2 48 35 PM" src="https://github.com/user-attachments/assets/37142072-2eb6-4146-977c-5133aa555831">


4. Finalizing the Visualization
After several iterations, the final version of the visualization was completed. It includes interactive features such as tooltips, zooming, and filtering, making it easy for users to explore the data.


## Analysis and Insights
-Compare Unemployment Rates Across Different States
The visualization allows users to compare unemployment rates for each state, identifying states with the highest and lowest unemployment rates. This comparison helps highlight regional disparities in unemployment.

-Analyze Trends in Unemployment Rates Over Time
By tracking unemployment rates over the years, the visualization reveals trends and seasonal patterns. Users can see how unemployment rates have changed over time and identify periods of economic downturn or recovery.

-Explore the Relationship Between Unemployment Rates and Economic Indicators
The project investigates correlations between unemployment rates and other economic indicators such as GDP growth and inflation rates. This analysis provides a broader economic context to the unemployment data.

-Examine the Distribution of Unemployment Rates
Histograms and box plots visualize the distribution of unemployment rates across states, helping to identify unusual patterns or outliers. This analysis can reveal states with consistently high or low unemployment rates.

-Identify States with High Unemployment Risk Factors
The dataset is used to identify states with high unemployment rates and analyze potential contributing factors. This analysis can help policymakers and researchers understand the underlying causes of high unemployment in certain areas.


## Visualizations
Bar Chart: Unemployment Rates Across States
<img width="992" alt="Screen Shot 2024-11-07 at 10 31 35 PM" src="https://github.com/user-attachments/assets/84910689-e55a-40a6-a791-9b86b1aa0b7b">
This bar chart visualization displays "Unemployment Rates Across States," with different shades of blue representing unemployment rates for various U.S. states.

-Color Coding: The use of darker shades of blue for higher unemployment rates works well for visual emphasis. The gradient gives a quick visual indication of which states have higher or lower rates.
-Labels: The percentage labels on top of each bar make it easy to compare unemployment rates across states at a glance, which is effective for data communication.
-Axis Titles: Both the x-axis (States) and y-axis (Unemployment Rate %) are clearly labeled, contributing to overall readability.
[https://vizhub.com/oabouhas/e9fc1b5c652e410682b2c5dabdf7ee2c](https://vizhub.com/oabouhas/7d7187da88d149d49551e6f5d54b3b09)

Bar Chart: the unemployment rates for 25 random states over 10 years
<img width="993" alt="Screen Shot 2024-11-14 at 1 05 07 PM" src="https://github.com/user-attachments/assets/2d2f6c15-9493-4592-9411-7b840bd23f16">
The project uses D3.js to create an interactive grouped bar
chart that visualizes unemployment rates across different
states over multiple years. The chart allows users to select
a specific year and view the corresponding unemployment
rates for each state.
Features Grouped Bar Chart: Displays unemployment rates for
each state, grouped by year. Tooltips: Provides additional
information when hovering over bars, showing the exact
unemployment rate for the selected year and state. Legend:
Indicates the colors corresponding to different years.
Hover: Hover over the bars to see the exact unemployment
rate for the selected year and state.
https://vizhub.com/oabouhas/47c2963a9a364d0bae7ec4654e179055


Bar Chart: the unemployment rates for 25 random states over 10 years with a dropDown
<img width="990" alt="Screen Shot 2024-11-14 at 1 09 14 PM" src="https://github.com/user-attachments/assets/cbdf1b71-9e7d-42b8-8297-3b3fc81cb73c">
an interactive grouped bar chart that visualizes unemployment rates across different states over multiple years. The chart allows users to select a specific year and view the corresponding unemployment rates for each state.

Features Grouped Bar Chart: Displays unemployment rates for each state, grouped by year. Interactive Dropdown: Allows users to select a year and update the chart dynamically. Tooltips: Provides additional information when hovering over bars, showing the exact unemployment rate for the selected year and state. Legend: Indicates the colors corresponding to different years. Hover: Hover over the bars to see the exact unemployment rate for the selected year and state. Select Year: Use the dropdown menu to select a different year and update the chart dynamically.
https://vizhub.com/oabouhas/5e31e71e07b243db9305f38887d278d7

Bar Chart: the unemployment rates for each state from 1990 to 2010
<img width="991" alt="Screen Shot 2024-11-14 at 1 12 10 PM" src="https://github.com/user-attachments/assets/c0d59cbf-65d4-4b85-ab75-0d2f1d934f29">
an interactive grouped bar chart that visualizes unemployment rates across different states over multiple years. The chart allows users to select a specific year and view the corresponding unemployment rates for each state.

Features Grouped Bar Chart: Displays unemployment rates for each state, grouped by year. Interactive Dropdown: Allows users to select a year and update the chart dynamically. Tooltips: Provides additional information when hovering over bars, showing the exact unemployment rate for the selected year and state. Legend: Indicates the colors corresponding to different years. Hover: Hover over the bars to see the exact unemployment rate for the selected year and state.
https://vizhub.com/oabouhas/714e632e9dee49309364e9ca2e2784db


Scatter Plot: Unemployment Rate vs Population

<img width="1251" alt="Screen Shot 2024-10-10 at 10 13 14 AM" src="https://github.com/user-attachments/assets/5ebe9f5e-07e1-41b5-a04a-e5053440ca64">
This project visualizes the relationship between the population and unemployment rate across different US states over time using a scatter plot.

X-axis: Total population of a state
Y-axis: Unemployment rate in the state
This visualization aims to provide insights into the employment status in different US states over time.

https://vizhub.com/oabouhas/unemployment-rate-vs-population-scatter-plot-visualization

Histogram: Distribution of Unemployment Rates

<img width="963" alt="Screen Shot 2024-10-22 at 6 02 47 PM" src="https://github.com/user-attachments/assets/5de53a94-167f-4864-b167-fd71aa280a93">
This graph visualizes the distribution of unemployment rates in the US for the year 2022 using a colored histogram. The histogram bars are colored based on the unemployment rate.

X-axis: Unemployment rate
Y-axis: Number of states
The histogram uses D3.js to render the bars and color them based on the unemployment rate. 
https://vizhub.com/oabouhas/c9421d4fae384fdbb4afef6d39ebf7aa

Bubble Map: Unemployment Rates in the US

<img width="964" alt="Screen Shot 2024-10-22 at 6 05 24 PM" src="https://github.com/user-attachments/assets/c0109ba7-9d9a-4360-a565-6268f37232b2">

This project visualizes the unemployment rates in the US in 2022 using a bubble map. Each bubble’s size and color represent the unemployment rate for each state.
https://vizhub.com/oabouhas/29044359fb9045d681a1ebc87b522580

Unemployment Rate Box Plot Visualization
<img width="969" alt="Screen Shot 2024-10-30 at 10 41 40 PM" src="https://github.com/user-attachments/assets/a3a593b9-2d2e-4d58-bff4-9b430526c7bc">

This project visualizes unemployment rate data across various U.S. states for the year 2020. Using D3.js, it presents a box plot to highlight the distribution of unemployment rates, showing median, quartiles, and range (min-max) for each state. This is part of a data visualization project aimed at making statistical data on employment more accessible and insightful.

https://vizhub.com/oabouhas/80ed8790b9f1420dac9be35c6d28920b


Unemployment Rate Heatmap
<img width="964" alt="Screen Shot 2024-11-07 at 11 44 17 AM" src="https://github.com/user-attachments/assets/2bf6d226-3ea6-436f-a215-eea8a86d641d">

U.S. Unemployment Rates Heatmap Overview This visualization
displays the monthly unemployment rates across selected U.S.
states in the form of a heatmap. Each cell in the heatmap
represents the unemployment rate for a specific state and
month. The heatmap colors range from lighter shades for
lower unemployment rates to darker shades for higher rates,
providing a quick visual comparison across states and time.

Features Color-Coded Heatmap: Each cell’s color represents
the unemployment rate, with darker colors indicating higher
rates. Interactive Tooltip: Hovering over a cell shows
detailed information about the state, month, and
unemployment rate. Legend: A vertical legend on the right
shows the color ranges and their associated unemployment
rate thresholds, helping interpret the heatmap colors. Color
Scale The color scale is divided into discrete ranges to
capture the variance in unemployment rates 

[https://vizhub.com/oabouhas/347dee7845ba4490a2826b587ba3af08](https://vizhub.com/oabouhas/347dee7845ba4490a2826b587ba3af08)


Pie Chart unemployment across various U.S. states.
<img width="980" alt="Screen Shot 2024-11-15 at 5 53 02 PM" src="https://github.com/user-attachments/assets/f73c507e-da24-4460-b35a-ddcfdbc75797">
This project is a D3.js-based interactive pie chart visualization, showcasing the proportion of unemployment across various U.S. states. It leverages dynamic data filtering, interactive elements, and animations to create an engaging user experience.
Features
Dynamic Data Representation

Visualizes the unemployment percentage for up to 30 states using a pie chart.
Automatically calculates the proportion of each state based on total unemployment.
Interactivity

Slice Hover Interaction:
Hovering over a slice displays the state name, unemployment percentage, and value in a tooltip.
Slices expand slightly when hovered over for better visibility.
Legend Interaction:
Hovering over a legend item highlights the corresponding slice in the chart.
Clicking a legend item filters data dynamically by region.
Click Interaction:
Clicking a slice updates the chart with the selected state displayed prominently.
Animations
Line Chart with Multiple Lines Unemployment Rates Comparison
<img width="972" alt="Screen Shot 2024-11-18 at 3 55 47 PM" src="https://github.com/user-attachments/assets/fdee1345-9fd8-440d-b74c-336d161f558d">

 This project visualizes the unemployment rates of selected US states over time using a line chart. The chart includes interactive features and a color-coded legend to indicate which color represents each state.

Features Interactive Line Chart: Hover over the lines to see the state names and highlight the selected line. Color-Coded Legend: A legend on the right side of the chart indicates which color represents each state. Responsive Design: The chart adjusts its size based on the container dimensions.

https://vizhub.com/oabouhas/8626a35aa0e34f18864d815d95142a33


## Milestones
- County-Level Data: I will attempt to source and integrate county-level unemployment data to provide more granular insights into unemployment patterns within each state.
- Multi-Line Chart (All States Over All Years): I plan to create a comprehensive multi-line chart that visualizes the unemployment rate trends across all states for each year. This will help in identifying long-term patterns, spikes, or trends at the state level.
- Choropleth Map: I will finalize the Choropleth Map, which will visually display the unemployment rates across U.S. states, color-coded by rate. This map will serve as a geographic overview of the unemployment landscape.
- Diverse Graph Types: I intend to employ a variety of graphs, such as bar charts, scatter plots, and time-series graphs, to explore different aspects of the data. This diversity in visualization will provide multiple perspectives and uncover hidden patterns within the dataset.

  
## Current Progress
- Choropleth Map: Currently working on it and will have it done by next week (Week 10).
- Multi-Line Chart: Currently working on it and will have it done by next week (Week 10).
- HeatMap: Currently working on it and will have it done by next week (Week 10).
- Bubble Map: Finished in Week 9.
- Colored Histogram: Finished in Week 9.
