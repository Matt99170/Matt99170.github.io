## Third Blog Post-Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) refers to a set of procedures for producing descreptive and graphical summaries of a dataset in order to maximize insight into the dataset.

I have identified a six set startegy to use for EDA.

* *Understnding the data*: Try to understand the data and identify your intended outcomes. Knowing your intended outcomes will help you realize where the main focus of your effort should be.
* Check for missing data: It is vital to identify how many samples (rows) and how many variables/features (columns) are in your dataset with missing values. If there is an extremely high amount of data missing for a feature then considerations can be made as to whether or not to completely remove this feature while at the same time being cognizant to any bias that may be introduced due to removal.
* Provide basic descriptions of your sample and features: We aim to characterize all our features as either continuous, discrete or categorical. This categorization helps us to decide what visualizations to choose in our EDA and what statistical methods we can apply to our data.
* Identify the shape or distribution of the data: Probability Density Functions (PDF) helps to identify the distribution of the continuous features while Probability Mass Functions (PMF) help to identify the distribution of the discrete features. Both the PDF and PMF tells us things about the data such as skewness and boundedness. Additionally, basic statistical concepts such as mean and variance can also help. The mean tells us the center of the distribution and the variance tells us the spread of the distribution.
* Identify significant correlations (if any): Correlation measures the relationship between two features. Scatter plots and very useful with identifying correlations.
* Spot outliers: Outliers are significantly different from other samples in your dataset and if not identified and properly addressed it may cause problems in performing the necessary statistical tasks.

The overall goal when doing EDA is to look at the data through descriptive and graphical summaries before making any assumptions. It can help identify erroes and help to better understand the distrinution of the data and any interesting replaionships among the features.

There are four EDA methods namely Univariate Non-Graphical, Univariate Graphical, Multivariate Non-Graphical and Multivariate Graphical. Since graphical methods present a complete pictorial representation of the data I feel that Univariate Graphical (for data with one feature) and Multivariate Graphical (for data with several features) are the more important methods.

While doing EDA some of the more improtant things to look for are missing values, shape/distribution of the data, relationships among the features and outliers.
