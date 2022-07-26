# NewYorkAirbnb
## Machine learning (ML) pipline for Predicting listing price of New York Airbnb 


### Instructions
We built two types of modeling: day-level modeling and person-level modeling. For the day-level modeling, the input is daily features and one partipants have multiplevalues for one daily feature. For the person-lvel modeling, we aggreate multiple daily values into one person feature, which is the input of the ml learning pipline.Two modeling processes share the same ML pipeline. The ML pipeline includes three basic ML models: Lasso regression (Lasso), Random Forest regression (RF), and XGBoost regression (XGB). The fundamental training process is leave-one-particiapnt-out cross-validation, and the evaluation metrics includes MSE and MAE.
#### Step 1: attach the file
#### Step 2: clean the dataset.
run final-exploratory.ipynb. Data cleaning part is contained in this file.
#### Step 3: Run the ML methods.
run the final-linear.ipynb, final-logistic.ipynb, final-knn.ipynb, final-Naive bayes.ipynb, final-tree models.ipynb
For the person-level modeling, run the person_model_lasso.ipynb, person_model_rf.ipynb, person_model_xgb.ipynb
#### Step 4: Model tuning. 
run the final-model tuning.ipynb to tune the models.

