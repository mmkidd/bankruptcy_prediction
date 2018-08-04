#Dataset Used:
https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data
Note that data is available as 5 seperate files, these files were combined in to a single dataset for use in my code.

#Packages Used:
- numpy
- scipy
- pandas
- sklearn
- seaborn (used for correlation heatmap)
- matplotlib (used for feature importance graph)
- visuals (custom package, used in previous homework and included with file)
- keras
- xgboost
- lightgbm
 
# Organization of code:
1. Data analysis, including benchmark random forest model.
2. Data augmentation/reduction (including outlier removal, PCA)
3. Model Implementation - Each model has it's parameters set, is fitted on the data, and then the model is saved, reloaded, and tested on validation data.
3.1 Support Vector Machines
3.2 Neural Networks
3.3 Gradient Boosting Methods
3.4 Extensions, including extra LightGBM and Ensemble models.
4. Models are applied to test data, includes bootstrapped confidence intervals.

# Pretrained models are included in the NN_models, RF_models, and SVM_models folders to save training time.