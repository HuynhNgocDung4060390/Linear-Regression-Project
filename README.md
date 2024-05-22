**I. Problem**

The used and remanufactured appliance market has grown significantly over the past decade as it provides cost-effective options for both consumers and businesses looking to save money when purchasing a machine. . Optimizing the lifespan of devices through used device trading also minimizes their environmental impact and helps with recycling and waste reduction. This is a sample data set of normalized prices of used and new remanufactured/used equipment.
The goal is to perform data analysis and apply predictive models to be able to value used equipment.

**II. EDA**

Here is a data sheet of used devices along with their resale prices. The data table consists of 3250 rows.
Overview of the standards of the most purchased used devices:
-Brand: Samsung (Because Others is a combination of many other brands)
-Android
-4G: Yes
-5G: Yes
-Screen size: 12.8cm
-Rear camera: 8 MP
-Front camera: 5MP
-Internal memory: 32GB
-RAM: 4GB
-Battery: 3000 mAh
-Weight: 158 g
-Year of release: 2015
-Number of days of use: 706 days

![image](https://github.com/HuynhNgocDung4060390/Linear-Regression-Project/assets/150424521/fa87a190-78fc-4e37-9645-6e49662e179c)


**II. Linear Regression Project**

**1. Choose variable**

![image](https://github.com/HuynhNgocDung4060390/Linear-Regression-Project/assets/150424521/c074fe8e-ea51-43ca-b7f6-74d3a4dea24a)

**2. Model training**

![image](https://github.com/HuynhNgocDung4060390/Linear-Regression-Project/assets/150424521/58e6e47f-72ef-454f-81f3-15a11ad1629b)

Through the above summary, the R-squared (R2) value of 0.825 indicates that the univariate regression model is capable of explaining about 82.5% of the variance (variation) of the dependent variable ("normalized_used_price" ) equals the independent variable. This shows that the model is capable of explaining about 82.5% of the variation in used device prices through dependent values ​​such as current price, battery capacity, screen size, rear camera. and Front camera.4.1.1.2. Test the model

**3. Test the model**

Next, we will test the results of the model against the test data set:

![image](https://github.com/HuynhNgocDung4060390/Linear-Regression-Project/assets/150424521/b1d6c105-f8ef-4fac-9922-d0d3261bd7e9)

-The RMSE result is 0.24, showing that the model has the ability to predict accurately and close to the actual value.
-The MAE result is 0.1976, showing that the model has a very low average error and the prediction is close to the actual value.
-The R-squared result is 0.8368 which means the model has explained about 83.68% of the variation of the dependent variable (normalized_new_price) by the independent variables. This shows that the model has good ability to explain and predict the dependent variable.

**4. Forecast**

Suppose a used device with current price is 10 USD, battery capacity is 3000mAh, screen size is 10 inches, Rear camera is 8 MP and Front camera is 5MP

![Uploading image.png…]()

Suppose a used device with current price is 10 USD, battery capacity is 3000mAh, screen size is 10 inches, Rear camera is 8 MP and Front camera is 5MP


We have a prediction that the device will be resold for $6
