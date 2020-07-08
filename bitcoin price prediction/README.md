### The main goal of this project is to build a reliable model that predicts the price of bitcoin. Two methods were used so far:
1. Regression model. These do not perform very well
2. Tree-based methods. One of the built models is very promising, the model is wrong by 4% of the true price on average, and over 85% of tested predictions is wrong by less than 10%. This model is a very good starting point for further work and it will be certainly continued

Files description:
- data_cleaning - folder where data downloaded from the Internet are stored, is contains a jupyternotebook file, in which a dataset is created
- data_analysis - a file where the dataset is analyzed (charts, correlation matrix etc.)
- BTC_regression - a notebook with regression models
- BTC_treebased_models - a notebook with tree-based methods, it contains the promising model mentioned above
- tree.jpg - a schemta showing the way of proceeding with tree-based models
