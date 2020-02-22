# Patient-Switch-Prediction
Developed an ML model to predict if a patient would switch from their current medical regimen

## Dataset: https://www.kaggle.com/kksienc/armanik-patient-drugswitch

Please make sure that all the requirement(libraries) in the requirements.txt are installed.
Python 3.6 was used for develpment.

This script will work post the data preprocessing script is run.
Pass in the directory where the processed data is stored. This can be passes in the second cell of the lgbm.ipynb notebook.

For Feature Creation:
1. Run recency_feature_creator.py
2. Run frequency_feature_creator.py

Model.py is the python script that will generate the final solution. Output of this notebook is
1) final_sub.csv (predictions for the test set)
2) feature_importance.csv (feature importance list)
3)hard_classes.csv (this is the hard classes file)

