# U-net Road and Land Project Startup Instructions

This guide provides instructions for running the U-net architecture for road extraction and land classification projects using Google Colab. Note that the provided notebooks will include the training procedures for both models.

## Introduction
These instructions will guide you through the process of training U-net models for road extraction and land classification. The land classification model utilizes the dataset available at [DeepGlobe Land Cover Classification Dataset](https://www.kaggle.com/datasets/balraj98/deepglobe-land-cover-classification-dataset), while the road extraction model uses the dataset available at [DeepGlobe Road Extraction Dataset](https://www.kaggle.com/datasets/balraj98/deepglobe-road-extraction-dataset).

## Steps to Run the U-net Road and Land Project

1. Open Google Colab

   Open a web browser and navigate to https://colab.research.google.com.

2. Import the Selected Notebook

   In Google Colab, select "File" in the main menu, then choose "Open Notebook".

3. Choose Runtime Environment

   Ensure you have access to the appropriate runtime environment. Select "Runtime" from the main menu, then choose "Change runtime type". Choose the desired option, such as CPU, GPU, or TPU, depending on the available resources.

4. Change the Data Directory Path

   In the notebook cell referring to the data directory (`drive-dir`), ensure that the path to the main directory is modified. Download both datasets and place them in separate folders named `land-dataset` and `road-dataset`.

5. Execute the Notebook

   Click "Runtime" in the main menu and select "Run all" to execute all notebook cells, or run cells one by one (recommended, especially if you do not want to retrain the model but only load an existing one).
