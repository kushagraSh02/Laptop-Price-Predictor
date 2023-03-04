# Laptop-Price-Predictor
Predicting Laptop Price using its features using regression.


First We preprocess the data, we extract the important features from data, encode them and finally select top 20 features based on their correlation score with the target variable. 

Then We use random forest regressor to build a model to predict the price of laptops based on the selected 20 features.

Our model achieves 81% accuracy, which we can improve further by optimizing the model(Not done here).

About Data:
1 Company- String -Laptop Manufacturer

2 Product -String -Brand and Model

3 TypeName -String -Type (Notebook, Ultrabook, Gaming, etc.)

4 Inches -Numeric- Screen Size

5 ScreenResolution -String- Screen Resolution

6 Cpu- String -Central Processing Unit (CPU)

7 Ram -String- Laptop RAM

8 Memory -String- Hard Disk / SSD Memory

9 GPU -String- Graphics Processing Units (GPU)

10 OpSys -String- Operating System

11 Weight -String- Laptop Weight

12 Price_euros -Numeric- Price (Euro)

Dataset URL: https://www.kaggle.com/datasets/muhammetvarl/laptop-price
