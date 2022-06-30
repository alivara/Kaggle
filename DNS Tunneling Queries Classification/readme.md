# Running the Models
This part will run the model with 
- GaussianNB()
- SkopeRules
[Skope-Rules](https://github.com/scikit-learn-contrib/skope-rules) is an interpretable rule-based model consisting of a series of if then rules. <br>
 The algorithm is composed of three steps:
   1. BAGGING ESTIMATOR: the algorithm trains a tree-based model predicting the target and uses it to create these decision rule.
   2. PERFORMANCE FILTERING: from this set of rules an initial screening is carried out based on precision and recall thresholds.
   3. SEMANTIC DEDUPLICATION: the last filter applied for the choice of rules is based on a criterion of similarity between terms. 
   - The measure of similarity of two rules is determined by how many terms they have in common.
- DecisionTreeClassifier \
and 8,16,24,30 number of features to test the model.
