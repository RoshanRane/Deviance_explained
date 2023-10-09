# Deviance Explained
Deviance Explained metric implemented in python. Deviance Explained is a useful metric for evaluating machine learning models performing classification. It is a quantity between 0 (model fit is chance-level) and 1 (model fit is perfect). It is similar to $R^2$ in regression tasks[1] and is also referred to as pseudo-R-squared.

This implementation is based on McFadden’s equation[2].

### How to use
Simply use the `explained_deviance(y_true, y_pred_probas)` function in `deviance.py`. All dependant packages are in the imported in the python file. 
The function should same as [any other sklearn metric](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.explained_variance_score.html#sklearn.metrics.explained_variance_score).
 
#### References:

[1] _Eduardo García-Portugués_ Lab notes for Statistics for Social Sciences II: Multivariate Techniques: https://bookdown.org/egarpor/SSS2-UC3M/logreg-deviance.html 

[2] _McFadden, D. (1974)_ “Conditional logit analysis of qualitative choice behavior.” Pp. 105-142 in P. Zarembka (ed.),
Frontiers in Econometrics. Academic Press.
