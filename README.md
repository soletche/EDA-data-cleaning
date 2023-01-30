# EDA-data-cleaning
In this project I will focus on cleaning and preprocessing a dataset so that it can then be used to train a model.
By the end of this project, we will have a clean, preprocessed dataset ready to be used within a model. Through this process, we gain a deeper understanding of the importance of data cleaning and pre-processing, and how to apply these techniques in a real context.

With scatter_matrix we initially see correlations
![imagen](https://user-images.githubusercontent.com/114614816/215427941-5542caf6-f0b1-4fa0-97d3-ae22a51605fc.png)

We analyze nulls, and distributions of variables, for example in this case the prior and post distribution applying log

![imagen](https://user-images.githubusercontent.com/114614816/215428847-fd48c0f3-07b1-4b40-ad83-c742abadf46b.png)

**IterativeImputer** for numeric variables to predict NA based on the other variables, and on the other hand **SimpleImputer** with the "most frequent" strategy for categorical variables.

In summary, nulls, duplicates, evaluation of each type of variable are analyzed, and everything is passed to numeric values. Distributions are seen to be able to finally evaluate the correlation of the variables.
