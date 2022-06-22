##  Overview
We are a data science consulting company looking to provide predictive and actionable insights regarding sale pricing for relators.The analysis of variables such as price, price per square foot, distance from Seattle using latitude and longitudes, and number of bedrooms and bathrooms. 

Our presentation, where we analyze our dataset can be found at:

We are a data science consulting company working with predictive sale pricing for relators. (price the home to sell)


## Data Understanding and Analysis

This project uses the King County House Sales dataset, which can be found in  `kc_house_data.csv` in the data folder in this assignment's GitHub repository. The description of the column names can be found in `column_names.md` in the same folder. As with most real world data sets, the column names are not perfectly described, so you'll have to do some research or use your best judgment if you have questions about what the data means.


### Key Points

* **Your goal in regression modeling is to yield findings to support relevant recommendations. Those findings should include a metric describing overall model performance as well as at least two regression model coefficients.** As you explore the data and refine your stakeholder and business problem definitions, make sure you are also thinking about how a linear regression model adds value to your analysis. "The assignment was to use linear regression" is not an acceptable answer! You can also use additional statistical techniques other than linear regression, so long as you clearly explain why you are using each technique.

* **You should demonstrate an iterative approach to modeling.** This means that you must build multiple models. Begin with a basic model, evaluate it, and then provide justification for and proceed to a new model. After you finish refining your models, you should provide 1-3 paragraphs in the notebook discussing your final model.

* **Data visualization and analysis are no longer explicit project requirements, but they are still very important.** In Phase 1, your project stopped earlier in the CRISP-DM process. Now you are going a step further, to modeling. Data visualization and analysis will help you build better models and tell a better story to your stakeholders.




### GitHub Repository

Recall that the GitHub repository is the cloud-hosted directory containing all of your project files as well as their version history.

The requirements are the same as in [Phase 1](https://github.com/learn-co-curriculum/dsc-phase-1-project-v2-3#github-repository), except for the required sections in the `README.md`.

For this project, the `README.md` file should contain:

* Overview
* Business and Data Understanding
  * Explain your stakeholder audience here
* **Modeling**
* **Regression Results**
* Conclusion

## Modeling



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






### Data Preparation Fundamentals

We define this objective as:

> Applying appropriate **preprocessing** and feature engineering steps to tabular data in preparation for statistical modeling

The two most important components of preprocessing for the Phase 2 project are:

* **Handling Missing Values:** Missing values may be present in the features you want to use, either encoded as `NaN` or as some other value such as `"?"`. Before you can build a linear regression model, make sure you identify and address any missing values using techniques such as dropping or replacing data.
* **Handling Non-Numeric Data:** A linear regression model needs all of the features to be numeric, not categorical. For this project, ***be sure to pick at least one non-numeric feature and try including it in a model.*** You can identify that a feature is currently non-numeric if the type is `object` when you run `.info()` on your dataframe. Once you have identified the non-numeric features, address them using techniques such as ordinal or one-hot (dummy) encoding.

There is no single correct way to handle either of these situations! Use your best judgement to decide what to do, and be sure to explain your rationale in the Markdown of your notebook.

Feature engineering is encouraged but not required for this project.

## Conclusion


## Next Steps



## Repository Structure 

