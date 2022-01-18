# Walmart-Store-Sales-Forecasting
A regression based modeling project to forecast the sales of Walmart.
Walmart is one of the largest retailers in the world and it is very important for them to have accurate forecasts for their sales in various departments.Since there can be many factors that can affect the sales for every department, it becomes imperative that we identify the key factors that play a part in driving the sales and use them to develop a model that can help in forecasting the sales with some accuracy.

For this project, we have used the dataset available from ‘Walmart Store Sales Forecasting’ project that was available on Kaggle. In this dataset, we have weekly sales data for 45 stores and 99 departments for a period of 3 years. In addition, we had store and geography specific information such as store size, unemployment rate, temperature, promotional markdowns etc. Using these factors, we needed to develop a regression model that can forecast the sales and is also computationally efficient and scalable.

## Stores:

Store: The Store number. Range from 1-45.

Type: Three types of stores ‘A’, ‘B’ , ’C’

Size: Sets the size of a store would be calculated by the no. of products available in the particular store ranging from 34,000 to 210,000.

## Features:

Temperature: Temperature of the region during that week.

Fuel_Price: Fuel Price in that region during that week.

MarkDown 1-5: Represents the Type of markdown and what quantity was available during that week.

CPI: Consumer price Index during that week.

Unemployment: The unemployment rate during that week in the region of the store.

## Sales: 

Date: The date of the week where this observation was taken.

Weekly_Sales : The sales recorded during that week.

Dept: One of 1-99 that shows the department.

IsHoliday: a Boolean value representing a holiday week or not.

# Conclusion:

In Conclusion, for this Walmart sales predication we used four different Machine learning techniques: Linear Regression Model, Random forest Regression Model, KNN regression Model, XG Boost Regression model and we find that our Random forest regression equation is quite accurate (97.88% accuracy). The analysis shows that in the april and December, store type A & B shows very high sales may be because of the special days like Good Friday and Christmas. High markdowns are not helping the sales. The relationship between the sales and temperature was varying with the each and every department. Hence, the above were the insights drawn by the analysis of the sales data of the Walmart.



