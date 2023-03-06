# Seoul-Bike-Sharing-Demand-Prediction

#### INTRODUCTION

  This is Seoul, one of the most populous cities in the world. With more than 10 million residents and a building density of 33,000 people per square kilometer, Seoul  has the perfect mix of urban sprawl and cozy neighborhoods. It's also home to one of the largest concentrations of bicycles in all the world—in other words, there's usually an empty bike for you when you need it. The city has been relying on a bike sharing system for years now to provide transportation services to its citizens. In many urban cities we can see bike station are providing bike facility for short distance. Riding bike every day also improves cholesterol level. The dataset contain numerical, categorical type of data, here we have two years of record of bike rented 2017 and 2018,and some other information like functioning day, humidity, temperature level, our project is we deal with various weather related fact to make accurate prediction without fail.

In many urban cities we can see bike station are providing bike facility for short distance. Riding bike every day also improves cholesterol level.The dataset contain numerical, categorical type of data, here we have two years of record of bike rented 2017 and 2018,and some other information like functioning day, humidity, temperature level, our project is we deal with various weather related fact to make accurate prediction without fail.

#### Problem Statement

Currently for the purpose of improving transportation facility, rented bike have been introduced in several urban and metropolitan cities. It is necessary in order to make rented bike accessible and availability to local public of that city at the appropriate time. Eventually, maintain the steady supply of rented bikes in the cities emerges as a top priority. Predicting the number of bikes needed to maintain a steady supply of rental bikes at each hour’s interval is essential.

#### Data Wrangling
Data wrangling is a term often used to describe during data analysis. It helps to transform data from one format into another. The aim is to make data more accessible.
These include things like data collection, exploratory analysis, data cleansing, creating data structures, and storage.

#### Comparison of all Evaluation matrix with respect to models
Aim of creating this data-frame is to give single view of each algorithms performance on our model. Store every evaluation matrix into a dictionary and models into list then make DataFrame which look like this.

![image](https://user-images.githubusercontent.com/78267410/223148925-36e140bd-7783-443b-acb7-f2d35ed211c1.png)

Here we present model performance after applying algorithm in descending order. Each algorithm presenting by different colour. As we can see Random Forest algorithm perform very well on our bike_sharing_demand model. As compare to Decision Tree, Linear Regression and Lasso, Ridge and Polynomial regression is least performing algorithm than
other.

#### Conclusion

1. We observed that Initially Bike sharing is not in demand but as time goes and many people got to know about it, they start using bicycle in daily purpose.

2. At eight in the morning and six in the evening, account for the highest rental bike counts. The graph shows some upward tendency from 5 AM to 8 AM; it reaches its peak at 8 AM and then undergoes a downward trend. The demand then progressively increases until 6 o'clock, when it peaks, and then gradually decreases until midnight.

3. We find pattern in peoples that when the weather is mild to sunny and even a little windy, we've seen that people prefer to hire bikes.

4. Also demand of bicycle is more in weekdays than weekend probably most of the people going to office through bike.

5. Bicycle rental rates have been found to be highest throughout the summer and autumn seasons and lowest during the winter.

6. We discovered that the number of bike rentals is lowest on days with poor visibility and high humidity.

7. After evaluating model with lots of algorithms we found Random Forest work well on model as compare to Decision tree, Linear Regression, Ridge, Lasso, and Polynomial Regression is least performing algorithm than other.


