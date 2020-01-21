# Introduction <br>
## Data<br>
The project focuses on exploratory data analysis of the vast NYC Airbnb data available from guests and hosts since 2008. The dataset describes the listing activity and metrics in NYC for 2019.For more details regarding the package, please refer to the Dataset.
<br>
## Goal<br>
The goal is to create a smart pricing model from this dataset. It will help customers understand the influencing factors affecting the price appropriately.Hosts too can base their pricing for their listings based on this model.
<br>
How does the the number of reviews, stay duration, availability and neighburhood vary in signficance to the price of the listing.
<br>
## Modeling <br>
My target variable is Price and I plan to model it with linear regression and compare the effects of different predictor variables on Price. Number or reviews, availability, duration of stay and the area would be strong predictors.
<br>
## Conclusion<br>
<ul>
<li>We refined and cleaned the data by dropping functions, replacing null values, removing outliers and converting any continious variable we could into binary or categorical.
<br></li>
<li>We analyzed neighbourhood boroughs, mean price and assessed the top listings available in each neighbourhood groups and the types of homes they were.
<br></li>
<li>It would have been better to have more depeer insight into the reviews - positive or negative, although we transformed the continious variables that were skewed to get a more clear learning.
<br></li>
<li>It is possible to analyze further with host_name and its significant affect on price as one would deem there are hosts who have multiple listings and are popular among the customers, which gives them the power to fix prices as they please.
<br></li>
<li>We have narrowed down the most influencial predictors running a linear regression model to predict the best prices for any listing that would be ideal based on various factors. There were both positive and negative correlations leading to this and we deduced that minimum number of nights stayed, reviews, availability are strong dependent variables on price.
<br></li>
<li>Observed Vs Precited pricing shown for NYC Airbnb properties in the top 5 most visited neighbourhoods.</li>
</ul>
