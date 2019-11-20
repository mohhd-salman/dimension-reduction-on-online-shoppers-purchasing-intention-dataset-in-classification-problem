# dimension-reduction-on-online-shoppers-purchasing-intention-dataset-in-classification-problem

Dataset source and information : https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset

Here at first i have visualize the dataset and then i have used three classification algorithm .
For dimension reduction i have used backward elimination process.
In backward elimination process we feed all the possible features to the model at first. 
We check the performance of the model and then iteratively remove the worst performing features one by one till the overall performance 
of the model comes in acceptable range.
The performance metric used here to evaluate feature performance is pvalue. 
If the pvalue is above 0.05 then we remove the feature,else we keep it.
Here we are using OLS model which stands for “Ordinary Least Squares”. 
This model is used for performing linear regression.

So here i measured the accuracy whenever a feature is removed from the dataset and compared their accuracy in a line chart.
