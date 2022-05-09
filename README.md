# Housing Rental Analysis for San Francisco

In this activity, use your data visualization skills, including aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.

# Instructions 

Use the san_francisco_housing.ipynb notebook to visualize and analyze the real-estate data.

Note that this assignment requires you to create a visualization by using hvPlot and GeoViews. Additionally, you need to read the sfo_neighborhoods_census_data.csv file from the Resources folder into the notebook and create the DataFrame that you’ll use in the analysis.

The main task in this Challenge is to visualize and analyze the real-estate data in your Jupyter notebook. Use the san_francisco_housing.ipynb notebook to complete the following tasks:

Calculate and plot the housing units per year.

Calculate and plot the average prices per square foot.

Compare the average prices by neighborhood.

Build an interactive neighborhood map.

Compose your data story.

# Compose your data story 

Import the required libraries and dependencies

# Import the data

Using the read_csv function and Path module, create a DataFrame by importing the sfo_neighborhoods_census_data.csv file from the Resources folder

# Calculate and Plot the Housing Units per Year¶

# Step 1: Use the groupby function to group the data by year. Aggregate the results by the mean of the groups.

Create a numerical aggregation that groups the data by the year and then averages the results.

# Step 2: Use the hvplot function to plot the housing_units_by_year DataFrame as a bar chart. Make the x-axis represent the year and the y-axis represent the housing_units.

# Step 3: Style and format the line plot to ensure a professionally styled visualization.¶

Create a visual aggregation explore the housing units by year

# Step 5: Answer the following question:

 What is the overall trend in housing_units over the period being analyzed?
 
 
