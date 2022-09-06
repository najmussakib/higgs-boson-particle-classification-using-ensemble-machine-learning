# Higgs-boson-particle-classification-using-ensemble-machine-learning
##  HIGGS BOSSON FORECASTING

- To keep it basic, according to one of the Big Bang Theories, the entire universe used to be a singular particle before a fuse called the Boson caused it to explode. 
- The `Higgs Boson` are a type of unstable subatomic particle that breaks down very quickly.  Scientist studies the decay of the collision and works backwards. To assist scientist in differentiating the background noise from the signal, some machine learning algorithms using pyspark are modelled to better predict the Higgs Boson.

- This is a `classification problem` to distinguish between a **signal process** which produces Higgs bosons and a **background process** which does not. 

## Dataset
- URL:  http://archive.ics.uci.edu/ml/datasets/HIGGS#
- The data has been produced using Monte Carlo simulations. 

- The first 21 features (columns 2–22) are kinematic properties measured by the particle detectors in the accelerator. 

- The last 7 features are functions of the first 21 features; these are high-level features derived by physicists to help discriminate between the two classes. 

## Attribute Information:

- The `first column` is the class label (1 for signal, 0 for background).
- Followed by the `28 features` (21 low-level(Primitive) features then 7 high-level(Derived) features).

## ML Models 
- Decision Tree Classifier
- Logistic Regression
- Random Forest Classifier
- Suppport Vector Machines
- Gradient Boosted Trees
