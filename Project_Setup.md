# Situation

The client, faced a challenge in understanding their customer behavior and travel patterns in order to make strategic decisions.
To tackle this challenge, client developed a two-step plan: to identify data sources and to analyze the data.

Using readily available data sources such as the Rewards program database and flight records, client had access to transaction-level data on 1.52 million customers 
who made 1.86 million trips between January 2013 and December 2014. This data included information on how and when trips were booked, customer demographics,
loyalty program status, and more.

We analyzed the de-identified data and identified insights related to customer segments, travel patterns, and other useful information.
The findings were presented to client, enabling the client to make data-driven decisions and gain a better understanding of their customers.

# Process Framework

The analysis process employed an adaptive approach, utilizing various techniques such as data pre-processing, feature reduction, sampling, and clustering to uncover insights.

Data pre-processing involved cleaning and transforming raw data into a format suitable for analysis.

Feature reduction was then applied to reduce the dimensionality of the data and extract the most relevant features.

Sampling techniques were used to select a representative subset of the data for analysis. 

Clustering techniques were also employed to group similar data points and identify patterns in the data.

Overall, this approach enabled the team to uncover useful insights and provide the client with actionable recommendations based on their data.

In overview, the following steps were taken:

* Data Pre-processing
* Data Aggregation
* Feature Selection and Engineering
* Data Exploration
* Sampling
* Clustering
* Recommendations and Insights

# Data Pre-processing

To ensure a clean and reliable dataset, the team began by filtering for the client's operated flight data. The next step involved handling null values through the use of data smoothening techniques, such as interpolation or imputation, to preserve the integrity of the data.

Data types were updated as necessary to ensure consistency and accuracy across all variables. To further refine the dataset, duplicate entries were identified and dropped, resulting in a streamlined and efficient data structure.
 
 # Data Aggregation
 
 The team performed data aggregation to extract meaningful insights from the dataset. The following key metrics were aggregated:

Count of journeys by class, including first class, economy, and others, to understand the demand for different classes of travel.
Count of class upgrades to identify trends in passenger behavior and preferences.
Count of discounts to evaluate the effectiveness of promotional offers and inform future marketing strategies.
Count of different booking channels to determine the most popular channels among customers.
Sum of the total amount spent by passengers to gain insights into revenue and customer spending behavior.
Sum of the number of trips taken by passengers to identify patterns in travel behavior.

By aggregating these metrics, the team was able to provide the client with a comprehensive overview of their operations and customer behavior. These insights could then be used to make informed decisions and improve the client's business performance.

# Feature Engineering
 
As part of the feature engineering process, the team created additional variables to enhance the analysis.

Dummy variables were created to represent categorical variables such as gender, age group, and other relevant characteristics. These variables were used to enable more granular analysis of the data and to identify trends and patterns that might not be apparent with the original variables alone.

Cost metrics were also derived, including total trips taken, amount spent, and discounts offered. These variables allowed for a more nuanced understanding of customer behavior and spending patterns.

Rewards-related variables were also included in the analysis, such as membership in loyalty programs and the booking source for each trip. These variables provided insight into the effectiveness of the client's rewards program and allowed for a more detailed understanding of customer preferences and behavior.

Overall, these feature engineering techniques allowed for a more robust analysis of the data, providing the client with a deeper understanding of their operations and customers.

# Feature Reduction
To reduce the dimensionality of the dataset and focus on the most important features, the team utilized principal component analysis (PCA).

PCA is a technique that identifies the most significant variables in a dataset and generates new variables (principal components) that capture the most variation in the data. By retaining only the most important principal components, the team was able to reduce the dimensionality of the dataset while retaining most of the relevant information.

This approach allowed for more efficient analysis and improved the accuracy of the insights derived from the data. By using PCA for feature reduction, the team was able to provide the client with a more focused and streamlined analysis that highlighted the most important factors impacting their business.

# Data Exploration



