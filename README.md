# LINEAR-DISCRIMINANT-TREES

The linear discriminant tree implemented here shows higher accuracy than sklearn's default decision trees.

In the inner optimization problem, scikit-learn's LDA finds a good split for the given two distinct groups of classes.  
In the outer optimization problem, exchange method (Yildiz and Alpaydin, 2005) is used to divide K classes into two groups.

## References
OT Yildiz, E Alpaydin - International Journal of Pattern Recognition and Artificial Intelligence, 2005