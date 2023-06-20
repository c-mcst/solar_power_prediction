# solar_power_prediction
## A demonstration of various machine learning models for predicting solar panel power output

Welcome. This is a small project I did in a couple of afternoons using ML to see how well I could predict 
the power output of the 
solar panels on my house. I train two models: a linear regression model, and a simple deep neural network. I compare the loss from each model to get an idea of how much I've improved my predictions, and I do some speculation about where this project should go in the future if I really want to know how much power my solar panels will be generating in a given half hour.

The Jupyter Notebook `solar_power_prediction.ipynb` should show you most of what you want to know. I've done my best to comment and document thoroughly so that you can follow along. If you want to run this notebook yourself, the two data files in CSV format included in this repo should be all you need. Do note that your results may vary slightly due to randomness in the DNN process. Feel free to get in touch if you have any questions. 


If you want to dive deeper into the data used in this notebook, as well as the decisions behind some of my variable choices, I recommend starting at NSRDB (https://nsrdb.nrel.gov/about/what-is-the-nsrdb). From there, you can look for papers and articles on how solar output is usually predicted for a given site.


### How to run this yourself:
Clone the repo and make sure all dependencies are met. Dependencies outside of Python 3.10's standard library are:

`numpy`
`pandas`
`tensorflow`
`matplotlib`
`seaborn`
`jupyter`
`requests` (if making API calls)


Use Jupyter to open the notebook and you should be able to run the models.
