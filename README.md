# Mammogram-Prediction


### Predicting whether a mammogram mass is benign or malignant
We have used the "mammographic masses" public dataset from the UCI repository (source: https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass)

This data contains 961 instances of masses detected in mammograms, and contains the following attributes:

BI-RADS assessment: 1 to 5 (ordinal) Age: patient's age in years (integer) Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal) Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal) Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal) Severity: benign=0 or malignant=1 (binominal) BI-RADS is an assesment of how confident the severity classification is; it is not a "predictive" attribute and so we will discard it. The age, shape, margin, and density attributes are the features that we will build our model with, and "severity" is the classification we will attempt to predict based on those attributes.

A lot of unnecessary anguish and surgery arises from false positives arising from mammogram results. If we can build a better way to interpret them through supervised machine learning, it could improve a lot of lives.
