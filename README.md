# Basic Pipeline for Exploratory Data Analysis

# Business Problem

In this section, we will create a basic **pipeline** for **exploratory data analysis(EDA)** which can be applied to various datasets with **one main function**.

[Kaggle Link of the Notebook](https://www.kaggle.com/code/trigenaris/basic-pipeline-for-exploratory-data-analysis)

Data sources are added under the **Examples on Datasets** title
____

### Current Features
* Importing dataset and creating a DataFrame instance.
* Presenting general information about the dataset (e.g. head, shape, description).
* Separating the categorical and the numerical features of the dataset.
* Analyzing the categorical and the numerical features of the dataset.
* Visualizing the categorical and the numerical features of the dataset.
* Analyzing the target for the each feature.
* Analyzing the highly correlated features to improve the DataFrame.

____

### Possible Future Improvements

* Printing better reports to improve legibility.
* More accessibility for the user.
* ~Bypassing irrelevant features from the analysis (e.g. id, user_id).~ **COMPLETED**
* ~Categorizing numerical targets for better target analysis.~ **COMPLETED**
* Encoding for the incompatible data types.
* Handling missing values in the dataset.

____

# Examples on Datasets

Current examples of the pipeline for the following datasets respectively:
* [Breast Cancer Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset/data)
    
    **Description:** <br>
    Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases, and affected over 2.1 Million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area.
    
* [Diabetes Dataset](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)
    
    **Description:** <br>
    This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
* [Hitters Dataset](https://www.kaggle.com/datasets/floser/hitters)
    
    **Description:** <br>
    This dataset was originally taken from the StatLib library which is maintained at Carnegie Mellon University. This is part of the data that was used in the 1988 ASA Graphics Section Poster Session. The salary data were originally from Sports Illustrated, April 20, 1987. The 1986 and career statistics were obtained from The 1987 Baseball Encyclopedia Update published by Collier Books, Macmillan Publishing Company, New York.
