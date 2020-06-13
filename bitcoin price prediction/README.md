### The main goal of this project is to build a reliable model that predicts the price of bitcoin. Two methods were used so far:
1. Regression models (linear and nonlinear regression). These models perform very poorly
2. Tree-based methods. One of the built models is very promising, the model is wrong by 4% of true price on average, and over 85% of tested predictions is wrong by less than 10%. This model is a very good starting point for further work and it will be certainly be continued

Files description:
- data_cleaning - folder where the raw data downloaded from the Internet are stored, is contains a jupyternotebook file, in which data are cleaned and the dataset is created (all prices with datetime index)
- BTC_data.CSV - the main dataset with prices and dates (without google search trends column)
- BTC_data2.CSV - a google search trends column is added
- BTC_multilinear_regression - a notebook with multilinear regression bitcoin price model
- BTC_nonlinear-regression - an extension of BTC_multilinear_regression notebook where nonlinear term are introduced
- BTC_treebased_models - a file with tree-based methods, it contains the promising model mentioned above
- tree.jpg - a schemta showing the way of proceeding with tree-based models
