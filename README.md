# Health Insurance Premium Predictor


##Technology Used
![image](https://github.com/sanjanaamara99/Intel_oneapi-Health-Insurance_premium_predictor/assets/127667720/aa390651-56b8-4cbb-a9dd-3a1555d3014a)
                                                       INTEL ONE API
          The oneAPI industry initiative Intel is spearheading will ensure that programming across diverse compute architectures is greatly simplified. The promise of oneAPI to deliver a single programming environment across multiple compute architectures is a vital tool to unlock the promise of heterogeneous computing.
          The Intel® oneAPI Base Toolkit (Base Kit) is a core set of tools and libraries for developing high-performance, data-centric applications across diverse architectures. It features an industry-leading C++ compiler that implements SYCL*, an evolution of C++ for heterogeneous computing.
          This initiative helps developers to successfully use Intel® oneAPI toolkits to develop high-performance, data-centric applications across diverse architectures. Whether you're an independent software vendor, independent developer, student, or professor, you can find the content, training, and support that you need.



## Table of Contents

- [Overview](#Overview)
- [Features](#Features)
  - [Installation](#Installation)
-[Process involved](#Process involved)
- [Usage](#Usage)
- [model training](#Model training)
- [Results](#Results)
- [Contributing](#Contributing)
- [conclusion](#Conclusion)


## Overview

The Health Insurance Premium Predictor is a machine learning project that predicts health insurance premiums based on various factors such as age, BMI, smoking status, and more. This tool can be used by individuals to estimate their potential health insurance costs and by insurance companies to assess risk and pricing strategies.

## Features

- Age
- Sex
- BMI
- Children
- Smoker
- Region
- Charges


### Installation
- pip install numpy
- pip install pandas
- pip install plotly
- pip install sklearn


 ##Process involved

- Importing Libraries and Dataset
Python libraries make it very easy for us to handle the data and perform typical and complex tasks with a single line of code.
Pandas – This library helps to load the data frame in a 2D array format and has multiple functions to perform analysis tasks in one go.
Numpy – Numpy arrays are very fast and can perform large computations in a very short time.
Matplotlib/Seaborn – This library is used to draw visualizations.

-using the panda’s data frame to load the dataset and look at the first five rows of it.

- using describe() observe the descriptive statistical measures of the continuous data available in the dataset.

- Exploratory Data Analysis
EDA is an approach to analyzing the data using visual techniques. It is used to discover trends, and patterns, or to check assumptions with the help of statistical summaries and graphical representations. While performing the EDA of this dataset we will try to look at what is the relation between the independent features that is how one affects the other.

-observe some of the observations which are shown in the above graphs:

Charges are on the higher side for males as compared to females but the difference is not that much.
Premium charged from the smoker is around thrice that which is charged from non-smokers.
Charges are approximately the same in the given four regions.

-A clear distinction can be observed here between the charges that smokers have to pay. Also here as well we can observe that as the age of a person increases premium prices goes up as well.

DATA PREPROCESSING

Data preprocessing is technique to clean the unusual data like the missing values,wrong data,wrong format of data,duplicated data and the outliers.In this data we can observe that there are no missing values and wrong data.The only thing we can need to check is for duplicates and presence of outliers.we can see that there are no outliers present in age column
Due to the presence of outliers present in bmi column we need to treat the outliers by replacing the values with mean as the bmi column consists of continuous data.We treated outliers.

-Model Development
There are so many state-of-the-art ML models available in academia but some model fits better to some problem while some fit better than other. So, to make this decision we split our data into training and validation data. Then we use the validation data to choose the model with the highest performance.

-After dividing the data into training and validation data it is considered a better practice to achieve stable and fast training of the model.We have identified the best random_state number for this data set as 42 .Now we fix this random_state and try with different ml algorithms for better score or accuracy.

Now let’s train some state-of-the-art machine learning models on the training data and then use the validation data for choosing the best out of them for prediction.

-Conclusion
the highest accuracy this means predictions made by this model are close to the real values as compared to the other model.The dataset we have used here was small still the conclusion we drew from them were quite similar to what is observed in the real-life scenario. If we would have a bigger dataset then we will be able to learn even deeper patterns in the relation between the independent features and the premium charged from the buyers.




   

## Usage

To use the Health-insurance-premium-predictor model, follow these steps:
1. prepare your input data in the csv format with the required features.
2. use the trained model to make predictions on the input data.

## Model training

Details about the model training process ,  data preprocessing, model selection , hyperparameters, evaluation of the dataset given.

## Results

this model determines the health insurance premium by predicting from the given data.

## Contributing

We welcome contributions to the health insurance premium predictor project.
Whether you're a data scientist,a developer,or someone with domain expertise in the insurance industry, your contributions can help improve and expand this valuable tool.

## Conclusion

![image](https://github.com/sanjanaamara99/Intel_oneapi-Health-Insurance_premium_predictor/assets/127667720/7d857301-e07f-4969-a6b9-8afe578e1b4d)







