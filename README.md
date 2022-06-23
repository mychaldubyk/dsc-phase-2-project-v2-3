##  Overview
We are a data science consulting company named The ABCD Team looking to provide predictive and actionable insights regarding sale pricing for realtors using the power of big data. We hope to create a complex model using several different independent variables that can swifty and effectively achieve pricing estimates closer to realized housing prices than both the comparable method often used by realtors as well as a simple linear regression model. 

Our presentation, where we analyze our dataset can be found at: 

## Business and Data Understanding 

We are sourcing the data for this project from the King County House Sales dataset, which can be found at `kc_house_data.csv` in the data folder in the GitHub repository. The column name descriptions can also be found in this data folder, under the name `column_names.md`. Our visualizations can also be found seperately in the visualization_images folder located in this repository. We will analyze a list of variables such as price, square feet of living space, condition of living space, whether or not the property is waterfront, distance from Seattle Art Musueum using latitude and longitudes, and number of bedrooms and bathrooms. 





## Modeling
![Square Feet of Living Space](visualization_images/sqftliving.png)



![Condition](visualization_images/condition.png)



![Waterfront Amenity](visualization_images/waterfront.png)



## Regression Results

Recall that communication is one of the key data science "soft skills". In Phase 2, we are specifically focused on Statistical Communication. We define Statistical Communication as:

> Communicating **results of statistical analyses** to diverse audiences via writing and live presentation

Note that this is the same as in Phase 1, except we are replacing "basic data analysis" with "statistical analyses".

High-quality Statistical Communication includes rationale, results, limitations, and recommendations:

* **Rationale:** Explaining why you are using statistical analyses rather than basic data analysis
  * For example, why are you using regression coefficients rather than just a graph?
  * What about the problem or data is suitable for this form of analysis?
  * For a data science audience, this includes your reasoning for the changes you applied while iterating between models.
* **Results:** Describing the overall model metrics and feature coefficients
  * You need at least one overall model metric (e.g. r-squared or RMSE) and at least two feature coefficients.
  * For a business audience, make sure you connect any metrics to real-world implications. You do not need to get into the details of how linear regression works.
  * For a data science audience, you don't need to explain what a metric is, but make sure you explain why you chose that particular one.
* **Limitations:** Identifying the limitations and/or uncertainty present in your analysis
  * This could include p-values/alpha values, confidence intervals, assumptions of linear regression, missing data, etc.
  * In general, this should be more in-depth for a data science audience and more surface-level for a business audience.
* **Recommendations:** Interpreting the model results and limitations in the context of the business problem
  * What should stakeholders _do_ with this information?


## Conclusion

Both our complex model and our polynomial model displayed a higher level of fit and prediction quality than the often used comparable method as well as our own simple linear regression model. Our preferred complex and polynomial model takes into account a larger number of factors when estimating the housing price, and is sensitive to rapidly evolving market trends. The predictions when using our model will both save the realtor time when making listing decisions, as well as creating a more accurate listing price. 
