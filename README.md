# Impact-of-Covid-19-Pandemic-on-Global-Economy
> Introduction:
 
 * The first wave of covid-19 impacted the global economy as the world was never ready for the pandemic.
   
 *It resulted in a rise in cases, a rise in deaths, a rise in unemployment, and a rise in poverty, resulting in an economic slowdown.

 *Here, you are required to analyze the spread of Covid-19 cases and all the impacts of covid-19 on the economy.

> Data Loading and Exploration:

 *Load transformed and raw COVID-19 data from CSV files into Pandas DataFrames
 
 *Examine the value counts and mode of the "COUNTRY" column in the transformed data.

> Data Aggregation and Preparation:

 *The code initializes empty lists for various variables.
 
 *It iterates through each unique country in the "COUNTRY" column and performs the following calculations:
 
 *Calculates the average HDI (Human Development Index) for each country in the transformed data DataFrame.
 
 *Calculates the total number of COVID-19 cases and deaths for each country in the raw data DataFrame.
 
 *Calculates the average STI (Stringency Index) for each country in the transformed data DataFrame.
 
 *Calculates the total population for each country in the raw data DataFrame.
 
 *The results are stored in the respective lists

> Dataframe Creation:

 *The code creates a new data frame called "aggregated_data" by combining the calculated variables and other columns.
 
 *The data frame is sorted by the "Total Cases" column in descending order and limited to the top 10 rows.
 
 *Two additional columns, "GDP Before Covid" and "GDP During Covid", are added to the DataFrame.

> Plotly Visualizations:

 *The code uses Plotly Express and Plotly Graph Objects to create various visualizations.

> Conclusion:

 *In this task, we studied the spread of covid-19 among the countries and its impact on the global economy. 
 
 *We saw that the outbreak of covid-19 resulted in the highest number of covid-19 cases and deaths in the united states.
 
 *One major reason behind this is the stringency index of the United States. 
 
 *It is comparatively low according to the population and also analyzed how the GDP per capita of every country was affected during the outbreak of covid-19.
