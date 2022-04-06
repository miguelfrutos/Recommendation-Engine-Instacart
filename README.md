# Recommendation Engine Instacart
Building a product recommendation engine using vector embeddings and the Instacart dataset

<img src="https://d26a57ydsghvgx.cloudfront.net/product/Customer%20Story%20Images/instacartlogo.png"  width=300, height=100 align="right" />

Author: Miguel Frutos Soriano

Contact: miguel.frutos@student.ie.edu

Subject: Analytics for Retail and Consumer Goods

Kaggle Competition: https://www.kaggle.com/competitions/instacart-market-basket-analysis/data

### GOAL - Kaggle Competition
The dataset for this competition is a relational set of files describing customers' orders over time. **The goal of the competition is to predict which products will be in a user's next order**. Given a user, a product, and the user's prior purchase history, predict whether or not the given product will be reordered in the user's next order

The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. 

For each user, we provide between 4 and 100 of their orders, with the sequence of products purchased in each order. We also provide the week and hour of day the order was placed, and a relative measure of time between orders. For more information, see the blog post accompanying its public release.

### REQUIREMENTS
- The input will be a product list or a user vector.
- The output is the list of products the algorithm recommends.

### EVALUATION CRITERIA
- The features used to train the model (How do you prepare the string data to be used? Hint: NLP transformations)
- The quality of the output. Measure qualitatively (Does the output make sense or not?)

### DELIVERABLES
- The code.
- Short description on the limitations / shortcomings of the model and how it could be improved in slide or text document format.

### STEPS
1. [Chapter 0 - Business Case Understanding](#ch0)
1. [Chapter 1 - Download the dataset](#ch1)
1. [Chapter 2 -  Run a jupyter lab/notebook or other python environment and load the data](#ch2)
1. [Chapter 3 -  Explore the data](#ch3)
1. [Chapter 4 -  Graph and derive insights from the data](#ch4)
1. [Chapter 5 -  Prepare and structure the data to be useable by the word2vec algorithm](#ch5)
1. [Chapter 6 -  Generate a vector model](#ch6)
1. [Chapter 7 -  Pre-model and Exploration](#ch7)
1. [Chapter 8 -  Visualizations with t-SNE](#ch8)
1. [Chapter 9 -  Use a spatial distance model like an annoy model](#ch9)
1. [Chapter 10 -  Test using either a user or product list vector](#ch10)
1. [Chapter 11 -  Explore the output and validate the results qualitatively](#ch11)
