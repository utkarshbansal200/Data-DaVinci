# **Welcome to Week 2 of Data DaVinci**

This week, we'll dive further into classification using machine learning. In the previous weeks, you have implemented K-means clustering and Logistic Regression (for multiple classes, we use the [softmax regression](https://www.youtube.com/watch?v=LLux1SW--oM) instead) which are both used for classification tasks.  

**Decision Trees** are a simple yet powerful tool for classification and regression tasks. They work by splitting data into subsets based on feature values, forming a tree-like structure of decisions. Each node in the tree represents a decision based on one feature, and the leaves represent the outcome or prediction.  

**Random Forests** improve on decision trees by combining multiple decision trees into an ensemble. Each tree in a random forest is trained on a random subset of the data, and the final prediction is made by averaging the results (for regression) or by taking a majority vote (for classification) across all the trees. This reduces the risk of overfitting, making the model more robust.

**Ensemble Methods** refer to techniques that combine multiple models to improve overall performance. By aggregating the predictions of different models, ensemble methods like Random Forests can often outperform individual models, especially when dealing with complex or noisy data. The idea is that by combining the strengths of multiple models, the ensemble is less likely to make the same mistakes.

This week has 2 assignments (all related data is present in the same directory):

- [Decision Trees](./Decision-Trees/)  
- [Random Forests](./Random-Forests/)

Resources:

- [Decision Tree Classifier](https://www.youtube.com/watch?v=_L39rN6gz7Y)
- [Decision Tree Regressor](https://www.youtube.com/watch?v=g9c66TUylZ4)
- [Random Forests](https://www.youtube.com/watch?v=J4Wdy0Wc_xQ)
- [Understanding overfitting](https://medium.com/analytics-vidhya/elucidating-bias-variance-under-fitting-and-over-fitting-273846621622)
- [Bagging vs Boosting](https://www.youtube.com/watch?v=tjy0yL1rRRU)
- [Ensemble Learning](https://www.ibm.com/think/topics/ensemble-learning#:~:text=Ensemble%20learning%20is%20a%20machine,than%20a%20single%20model%20alone.)
- [K-Nearest-Neighbours (a simple classifier)](https://www.geeksforgeeks.org/k-nearest-neighbours/)
