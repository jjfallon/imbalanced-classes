# Imbalanced classes

The notebooks in this project explore different ways of using classifiers when the data in question has imblanced classes. 
This serves as a quick overview introducing the main ideas and demonstrates the main approaches on one very simple example.

- **introduction.ipynb**: Introduction to class imbalance problems including: when it is an issue; overview of the different approaches; expressing it in terms of cost sensitive classifiers. This notebook then goes on to demonstrate the two approaches based on the theory of cost sensitive classifers. Firstly, predicting the lowest cost class (equivalent to varying the probability threshold for predicting the minority class in two class problems) and secondly, passing class weights to the classifier.
- **pre-processing.ipynb**: Exploration of a number of different approach to dealing with class imbalance involving pre-processing including oversampling, undersampling, MetaCost, and the use of balanced ensembles.
- **ranking.ipynb**: Demonstration of dealing with class imbalance by converting the classification problem to one of ranking the points in terms of the likelihood of being in the minority class. This ranking problem only considers pairs of data points where the classes differ and is, therefore, inherently balanced.
-
-
