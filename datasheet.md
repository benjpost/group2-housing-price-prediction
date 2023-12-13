# Datasheet for Housing Pricing Prediction Model Dataset

## Data Overview
- **Citation/Contact Info**: NeuralNine, "House Price Prediction in Python - Full Machine Learning Project" https://www.youtube.com/watch?v=Wqmtf9SA_kk&ab_channel=NeuralNine
- **Original Purpose of the Data**: The purpose of this dataset is to develop a predictive model that can estimate housing prices. It serves as a foundation for analyzing the correlation between the features of houses and their estimated market prices, which would allow for people to make informed decisions on analytics in real estate.

## Motivation
- **Why was it created?**: This dataset was created to provide a more accurate and efficient way to estimating the value of real estate properties, which is useful for both real estate analysis and individual decisions. It holds benefits to both real estate agents and families looking to buy new homes.
- **Stakeholders**: 
  - **Real Estate Agents**: Agents require accurate valuations to advise their clients on buying and selling decisions effectively. A ML model will also help them forecast this valuations. 
  - **Home Buyers and Sellers**: Everyday people would benefit from more accurate pricing, which ensures fair transactions and helps in cost planning.
  - **Data Scientists**: Professionals in the data science field can use data such as ours for developing more sophisticated models and further contributing to predictive analytics of house prices.
  - **Real Estate Appraisers**: Real Estate Appraisers would benefit greatly with a
     reliable models to support their valuations.
  - **Financial Institutions**: Banks could use a predictive model such as ours to assess the risk of loans and to change their pricings accordingly.

## Composition
- **Observations/Instances**: The dataset is a set of housing traits that are influential in determining the market price of a property. This includes quantitative features like square footage, number of bedrooms, number of bathrooms, the year built, and other data like neighborhood, which has been processed into a machine-readable format.
- **Biases of the metrics**: There is an some geographic bias in the dataset, as the data is collected from specific locations. Additionally, market trends and demographics that are not shown in the dataset could result in a biased model that does not generalize well to other regions or property types. This is related to the readings we've seen in the class, and how models can be skewed from bias; these biases can lead to models that do not accurately reflect realities in different regions or for various property types. 
We must also address the relational ethics behind models such as this one that can be easily skewed. For instance, it might lead to inaccurate property valuations in minority regions. This would lead to systemic inequalities and impact the economic well-being of these communities.
We should also consider the ethics of expediency as we talked about in class. A real estate agent could easily skew data for a ML model for their own gain, while ignoring the moral dilemmas behind it. We have to set parameters behind prediction models to make sure they can't be as susceptible to bias.
- **Summary statistical overview**: A comprehensive statistical summary is available through the provided , illustrating the distribution of each feature and their interdependencies.

## Collection Process
- **How was it collected?**: The dataset was compiled from a real estate listings found by our group.
- **Sampling method**: Sampling was taken purely from the raw data that we decided to work with. 