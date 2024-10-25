# Give Life: Predicting Blood Donations

![Blood Donation Image](https://github.com/yanny-alt/Give-Life-Predicting-Blood-Donations/blob/main/images/blood_donation.png)

"Blood is the most precious gift that anyone can give to another person — the gift of life." ~ World Health Organization

## Introduction

Blood transfusions save lives—from treating patients after serious injuries to managing chronic conditions and undergoing surgery. Ensuring an adequate supply of donated blood is crucial to public health. In this project, we leverage machine learning to predict if a blood donor will donate blood again within a given timeframe. Such forecasts are essential for blood supply managers, especially during critical times of need.

This project utilizes data collected from a mobile blood donation vehicle in Taiwan. Our goal is to predict whether a donor will donate blood again, thus assisting blood collection centers in planning and ensuring enough blood is available when needed.

## Project Overview

- **Project Type**: Binary Classification
- **Dataset**: Blood Transfusion Service Center Dataset (UCI Machine Learning Repository)
- **Goal**: To predict whether a donor will donate blood within a specified period.
- **Technologies**: Python, Pandas, Logistic Regression, TPOT (AutoML), Scikit-learn, Jupyter Notebook

## Problem Statement

Forecasting blood supply is a recurring challenge for blood donation centers. Unpredictable donation patterns can lead to an inadequate supply of blood, putting lives at risk. This project aims to address this challenge by predicting blood donations, thereby enhancing the efficiency of the donation process.

## Project Objectives

- Understand the patterns in donor behavior.
- Develop a predictive model to determine if a donor is likely to donate blood again.
- Assist blood donation centers in decision-making to optimize blood collection processes.

## Skills Demonstrated / Technologies Used

- **Python** for data analysis and machine learning.
- **Pandas** for data manipulation and exploration.
- **TPOT** for automating machine learning pipeline selection.
- **Logistic Regression** for predictive modeling.
- **Scikit-Learn** for machine learning tasks.
- **Jupyter Notebook** for organizing and documenting the project.

## Dataset Overview

The dataset used in this project was collected from the Blood Transfusion Service Center in Hsin-Chu City, Taiwan. It is structured based on a marketing model known as **RFMTC**, a variation of the **RFM** (Recency, Frequency, Monetary) model.

- **Recency (R)**: Number of months since the last donation.
- **Frequency (F)**: Total number of donations.
- **Monetary (M)**: Total blood donated in cubic centimeters.
- **Time (T)**: Months since the first donation.
- **Target (C)**: Binary variable indicating whether the donor donated blood in March 2007.

To explore the dataset further, [click here to access the data](https://github.com/yanny-alt/Give-Life-Predicting-Blood-Donations/blob/main/datasets/transfusion.data).

## Project Methodology

1. **Data Loading and Inspection**: Loading the dataset and performing exploratory data analysis to understand its structure and quality.
2. **Data Preprocessing**:
   - Creating a target column.
   - Normalizing data for better model performance.
3. **Model Selection**:
   - Using **TPOT** to automate the selection of an optimal machine learning pipeline.
4. **Model Training and Evaluation**:
   - Training a logistic regression model.
   - Evaluating the model's performance using metrics like AUC score.
5. **Model Interpretation**:
   - Analyzing which features contribute the most to the prediction.
  
   ![](https://github.com/yanny-alt/Give-Life-Predicting-Blood-Donations/blob/main/images/TPOT.jpg)

## Results

The predictive model developed in this project was evaluated using various metrics, including accuracy and AUC score. The results indicate that the model can effectively identify donors likely to give blood again, helping blood collection centers optimize their outreach and collection efforts.

## Conclusion

This project successfully developed a model capable of predicting future blood donations based on historical donor behavior. By employing automated machine learning tools like TPOT, we streamlined the model-building process and achieved promising results.

## How to Replicate the Analysis

To replicate the analysis in this project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yanny-alt/Give-Life-Predicting-Blood-Donations

2.  **Install Required Packages**:
   Make sure you have Python 3 and the necessary libraries installed. You can install the required packages using the following command:
    ```bash
    pip install -r requirements.txt

4. **Run the Jupyter Notebook**:
   Open a terminal and navigate to the project directory. Then, run the Jupyter Notebook to see the detailed analysis steps:
      ```bash
      jupyter notebook Blood_Donation_Prediction.ipynb  

Thank you for exploring this project! If you have any suggestions or questions, feel free to reach out.   
