Task 1: Exploratory Data Analysis (EDA) and Visualization of a Real-World Dataset
Introduction
During this task, I performed exploratory data analysis (EDA) on a real-world dataset, specifically the Airbnb Listings Dataset. 

# Loading the Dataset
I began by loading the Airbnb dataset using Pandas, which provided a comprehensive view of the data with approximately 49,000 observations and 16 columns containing both categorical and numerical variables. Initial exploration included inspecting the dataset’s shape, data types, and summary statistics to gain an overview of the data composition.

2. Data Cleaning
To ensure data quality and reliability for analysis, I performed the following cleaning steps:

Handling Missing Values: I identified missing values in several columns and applied appropriate imputation techniques or removed rows/columns where necessary to maintain dataset integrity.

Removing Duplicates: Duplicate entries were detected and removed to prevent bias in the analysis.

Managing Outliers: Using statistical methods and visualizations such as box plots and histograms, I detected outliers in numerical features like price and minimum nights. These outliers were carefully examined and treated to avoid skewing the results.

3. Visualizations
To better understand the data distribution and relationships, I created various visualizations:

Bar Charts: These were used to display the distribution of categorical variables such as room type, neighbourhood group, and host listings. For example, the bar chart revealed that “Entire Home/Apartment” was the most common room type listed.

Histograms: Numeric features like price and number of reviews were visualized using histograms to observe their distribution, skewness, and presence of extreme values.

Correlation Heatmap: A heatmap was generated to examine correlations among numerical variables, helping to identify potential relationships and multicollinearity that could influence further analysis or modeling.

4. Summary of Insights
From the EDA and visualization process, I derived several key insights:

The majority of listings were entire homes or apartments, predominantly located in Manhattan and Brooklyn.

Price distribution was heavily right-skewed, with most listings priced at lower ranges but a few extremely high-priced listings acting as outliers.

Certain hosts had multiple listings, with the top hosts managing hundreds of properties.

Correlation analysis indicated relationships between features such as number of reviews and availability, which could be useful for predictive modeling or business strategy.

Conclusion
This task enhanced my ability to perform thorough exploratory data analysis and visualization on real-world datasets. The insights gained provide a solid foundation for subsequent data-driven decision-making or machine learning tasks. The cleaning and visualization steps ensured that the data was well-understood and ready for further analysis or modeling.
