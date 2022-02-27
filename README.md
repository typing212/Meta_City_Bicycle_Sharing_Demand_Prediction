# Meta City Bicycle Sharing Demand Prediction
Machine Learning Project - use clustering, demand prediciton model, and demand level prediciton model combined with expected value to support bike-sharing companies' new market operation strategy. 

## Techniques
K-medians, LASSO, Random Forest, Cross Validation, Benefit-cost Matrix

## Content
First, we use clustering to divide the city into different management areas according to the location-related features and then evaluate the demand level of each new region. Then, build demand prediction models and demand level prediction models to find out the relationship between the demand and other features. Moreover, we established a benefit-cost matrix with domain knowledge and calculate the expected value to find the most profitable model.

## Dataset
The original data set is a nine-day data set of shared bicycles in a certain city from Apr.26th 2017 to May.4th 2017, including the number of bicycles used and the total number of bicycles, as well as other related factors that may affect the volume of use. There are 460300 records in the original data set without any missing values. Each record represents the information for a specific area in a specific hour. The dataset contains 28 features, which show information in five dimensions: number of shared bicycles, time, geographic location, geographic features and weather condition.

## Insights
Lasso linear regression is able to predict numeric demand quantity given geographical characteristics and hour. Though this is still a rough prediction model, it can be deployed in company’s dispatching system. The dispatching system, theoretically, integrated the data we predicted for next day with number of bikes remained in each area after peak hour and decide dispatch strategy. To furtherly solve the problem, it might need to introduce linear programming methods, e.g., Multi-Location Newsvendor Problem. 

![image](https://user-images.githubusercontent.com/92670749/155497746-e1005a3f-a195-4955-a762-353aaf72884e.png)

In the demand level prediction model, we convert a numerical prediction problem into a classification problem to extend its business application. We help bike sharing company to predict the demand level of any potential area that might be the new market way earlier than they begin to invest into the market. Demand level forecasting contributes a lot in business decision making in topics of market entry strategy, operation strategy, marketing activities, etc.

## Collaborators

Ke Ma

Mingzhe Xu

Nanhai Zhong

Xiao Liang
# Meta_City_Bicycle_Sharing_Demand_Prediction
