This is a concise synopsis of all regression based Machine Learning assignments along with associated datasets. I have taken a very basic step-by-step approach to help anyone understand it with ease and no prior knowledge. 

# Dependencies to execute the notebook:
1) Python 3.6.x
2) Pip installation manager
3) Jupyter Notebook
4) Numpy
5) Pandas
6) Matplotlib

# What is Regression ?

Single Variable Linear Regression is a technique used to model the relationship between a single input independent variable (feature variable) and an output dependent variable using a linear model i.e a line. The more general case is Multi Variable Linear Regression where a model is created for the relationship between multiple independent input variables (feature variables) and an output dependent variable. The model remains linear in that the output is a linear combination of the input variables.

# Polynomial Regression

The model in Polynomial Regression now becomes a non-linear combination of the feature variables i.e there can be exponential variables, sine and cosine, etc. This however requires knowledge of how the data relates to the output. Regression models can be trained using Stochastic Gradient Descent (SGD).

# Pros of Regression 

1) Fast to model and is particularly useful when the relationship to be modeled is not extremely complex and if you don’t have a lot of data.
2) Linear regression is simple to understand which can be very valuable for business decisions.

# Cons of Regression 

1) For non-linear data, polynomial regression can be quite challenging to design, as one must have some information about the structure of the data and relationship between feature variables.
2) As a result of the above, these models are not as good as others when it comes to highly complex data.


## References :
1) https://realpython.com/linear-regression-in-python/#simple-linear-regression
2) https://towardsdatascience.com/selecting-the-best-machine-learning-algorithm-for-your-regression-problem-20c330bad4ef
