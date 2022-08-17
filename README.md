# Diamond-price-prediction-Project
![image](https://user-images.githubusercontent.com/100846110/185215014-62f2d961-2831-488f-919b-f62a934c3d89.png)
## Objective:
The goal of the project is to build a model that can accurately predict the price of a diamond given its weight, quality and dimensional measurements.
## Dataset:
This classic dataset contains the prices and other attributes of almost 54,000 diamonds. There are 10 attributes included in the dataset including the target ie. price.
![image](https://user-images.githubusercontent.com/100846110/185215976-90c7645e-2995-4a71-b2dd-68eb7d0de285.png)


Feature description:

price price in US dollars ( 326−− 18,823)This is the target column containing tags for the features.

The 4 Cs of Diamonds:-

carat (0.2--5.01) The carat is the diamond’s physical weight measured in metric carats. One carat equals 1/5 gram and is subdivided into 100 points. Carat weight is the most objective grade of the 4Cs.

cut (Fair, Good, Very Good, Premium, Ideal) In determining the quality of the cut, the diamond grader evaluates the cutter’s skill in the fashioning of the diamond. The more precise the diamond is cut, the more captivating the diamond is to the eye.

color, from J (worst) to D (best) The colour of gem-quality diamonds occurs in many hues. In the range from colourless to light yellow or light brown. Colourless diamonds are the rarest. Other natural colours (blue, red, pink for example) are known as "fancy,” and their colour grading is different than from white colorless diamonds.

clarity (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best)) Diamonds can have internal characteristics known as inclusions or external characteristics known as blemishes. Diamonds without inclusions or blemishes are rare; however, most characteristics can only be seen with magnification.

Dimensions

x length in mm (0--10.74)

y width in mm (0--58.9)

z depth in mm (0--31.8)

diamands%20project%20%281%29.png

depth total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79) The depth of the diamond is its height (in millimetres) measured from the culet (bottom tip) to the table (flat, top surface).

table width of the top of the diamond relative to widest point (43--95)

A diamond's table refers to the flat facet of the diamond seen when the stone is face up. The main purpose of a diamond table is to refract entering light rays and allow reflected light rays from within the diamond to meet the observer’s eye. The ideal table cut diamond will give the diamond stunning fire and brilliance.
## OSEMN Pipeline:
I’ll be following a typical data science pipeline, which is call “OSEMN”-

1.) Obtaining the data is the first approach in solving the problem.

2.) Scrubbing or cleaning the data is the next step. This includes data imputation of missing or invalid data and fixing column names.

3.) Exploring the data will follow right after and allow further insight of what our dataset contains. Looking for any outliers or weird data. Understanding the relationship each explanatory variable has with the response variable resides here and we can do this with a correlation matrix.

4.) Modeling the data will give us our predictive power.

5.) INterpreting the data is last. With all the results and analysis of the data, what conclusion is made? What factors contributed most to employee turnover? What relationship of variables were found?

## Conclusion:
Thus we have built models that can accurately predict the price of a diamond based on its features and the best out of four(LinearRegression, DecisionTree, RandomForest, KNN, XGBRegressor) is XGBRegressor.

It can be usefull for predicting the price of a new diamond given with its some features based on trending prices of such diamond.
