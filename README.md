# Baby's First Neural Nets

I have spent the last few weeks reading François Chollet's textbook, Deep Learning With Python, after work. Chapter 4 is composed of walkthroughs of the application of neural networks to 3 tasks and code examples to execute given tasks. This repository contains my notebooks from these different deep learning tasks. Each notebook has both my code and notes on the data, model, key takeaways, and comments on what key code snippets accomplish.

Binary Classification of IMDB Reviews - For this tasks I vectorized IMDB review text and build a model to categorize the sentiment as either negative or positive.

Multiclass Classification of Reuters Newswires - For this task I vectorized Reuters newswires similarly to the IMDB reviews. Then used one-hot encoding to process the 46 possible classes, which represent 46 topics for the newswires. The final model classfies the newswires by topic.

Regression Prediction of Median Home Prices in Boston Neighborhoods - For this task I was working with a small toy dataset of median housing prices of Boston neighborhoods. Each sample had another 13 features of things such as crime rates. I built a model with limited layers (to avoid overfitting) and used K-fold validation to tune it. 

I'm excited to keep working through Chollet's book and a few online courses. More mini-projects to come!

