# [DNN]-[Wine] Wine quality prediction with a Dense Network

This Kaggle notebook provides a step-by-step implementation of a simple prediction task using dense neural network (DNN) on the popular Wine Quality dataset.

The [Wine Quality datasets](https://archive.ics.uci.edu/ml/datasets/wine+Quality) consist of analyses of a large number of wines, each with an associated quality score ranging from 0 to 10. The dataset was provided by:
- Paulo Cortez, University of Minho, Guimarães, Portugal, http://www3.dsi.uminho.pt/pcortez
- A. Cerdeira, F. Almeida, T. Matos, and J. Reis, Viticulture Commission of the Vinho Verde Region (CVRVV), Porto, Portugal, @2009

You can retrieve the dataset from [University of California Irvine (UCI)](https://archive-beta.ics.uci.edu/ml/datasets/wine+quality).

Due to privacy and logistical concerns, only physicochemical and sensory variables are available in the dataset. Information such as grape types, wine brands, and selling prices is not included. The dataset features the following variables:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (score between 0 and 10)

The notebook is organized into three distinct sections:

## Objectives:
- Predict the quality of wines based on analysis data.

## Steps:
1. **Imports & Constants & Methods**
2. **Retrieve the data:** Obtain the wine quality dataset from the provided source.
3. **Prepare the data:** Perform necessary preprocessing and cleaning of the dataset.
4. **Build a model:** Design and construct a dense neural network (DNN) model for wine quality prediction.
5. **Train and save the model:** Train the DNN model using the prepared dataset and save the trained model for future use.
6. **Evaluate the model:** Assess the performance of the trained model by evaluating its predictions on test data.
7. **Evaluate the best saved model:** Assess the performance of the trained bast model saved by the callback, by evaluating its predictions on test data.
8. **Make predictions:** Apply the on the best trained model to make predictions on new, unseen wine data.

![DNN](dnn.png)

# Project:

- [Github](https://github.com/YanSteph/DNN-Wine-quality-prediction-with-a-Dense-Network/blob/main/dnn-wine-wine-quality-prediction-with-dnn.ipynb)
- [Kaggle](https://www.kaggle.com/code/yannicksteph/dnn-wine-wine-quality-prediction-with-dnn)


