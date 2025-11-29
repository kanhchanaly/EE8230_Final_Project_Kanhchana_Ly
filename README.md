# EE8230_Final_Project_Kanhchana_Ly
Abstract: Physiochemical properties of wine can provide insights into its alcohol content, which can be used both to label the final product’s alcohol percentage and to predict the overall wine quality. This project develops a regression model to predict the alcohol content of white wine using the UC Irvine white wine dataset. Exploratory data analysis was used to analyze the data distribution and pairwise correlation. Multiple regression models were evaluated and compared, with the Light Gradient Boosting Machine (LightGBM) outperforming the others. Tuning and a bagging ensemble approach were used to further improve the variance and performance of the model. The final bagged LightGBM model achieved an R2 = 0.9506, MAE = 0.2127, and RMSE = 0.2740 when used to predict on the unseen dataset. These results demonstrate that ensemble tree-based methods can effectively predict alcohol content from the physiochemical properties.

Presentation link: 

The main files include:
- README.md: current file
- winequality-white.csv: the csv file of the dataset
- Kanhchana-Ly-Final-Project-EE8230.ipynb: notebook containing the analysis and pipeline for the trained model

The trained model was also deployed at HugginFace at: https://huggingface.co/spaces/kanhchanaly/white_wine_regression_alcohol_prediction

The corresponding files for building the space are also provided here:
- README_Hugginface.md: readme file for huggingface
- app.py
- requirements.txt
- white_wine_regression_model.pkl: saved model in .pkl format
- .gitattributes

