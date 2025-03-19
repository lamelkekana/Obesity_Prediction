# Obesity_Prediction

![Image](https://github.com/lamelkekana/Obesity_Prediction/raw/main/scale_image.jpg)

## 📌 Table of Contents
- [📌 Overview](#-overview)
- [📊 Dataset Description](#-Dataset-Description)
- [🎯 Objectives](#-Objectives)
- [🔄 Notebook Workflow](#-Notebook-Workflow)
- [📦 Packages](#-Packages)
- [🖥️ Environment Setup](#-Environment-Setup)
- [📂 Opening the Jupyter Notebook File](#-Opening-the-Jupyter-Notebook-File)
- [📝 License](#-License)


### 📌 Overview

This repository contains a Jupyter Notebook that predicts obesity levels based on various features such as age, height, weight, gender, and lifestyle factors. The notebook performs data preprocessing, feature engineering, model training, and evaluation to predict different obesity classes.

### 📊 Dataset Description

This dataset contains information for estimating obesity levels in individuals from Mexico, Peru, and Colombia, based on their eating habits and physical condition. It includes 17 attributes and 2,111 records, with each record labeled by the class variable 'Obesity' (Obesity Level), which classifies individuals into the following categories: Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, and Obesity Type III.

### 🎯 Objectives

The objective of this analysis is to classify individuals into different obesity levels based on the features mentioned above, using machine learning techniques such as Support Vector Machine (SVM) and Logistic Regression.

### 🔄 Notebook Workflow
- __Data Loading:__ The notebook begins by loading the dataset and inspecting its structure.
- __Data Preprocessing:__ Missing values, outliers, and categorical variables are handled. Feature encoding (Label Encoding & One-Hot Encoding) is applied where needed.
- __Exploratory Data Analysis (EDA):__ Various visualizations and statistics are used to understand the distribution of features and the relationships between them.
- __Model Training:__ Machine learning models (SVM and Logistic Regression) are trained on the dataset to predict obesity levels.
- __Model Evaluation:__ The models' performance is evaluated using accuracy, precision, recall, F1-score, and other metrics.
- __Conclusion:__ Key insights are drawn from the analysis, and recommendations are provided for improving obesity prevention.

### 📦 Packages 

🐼  pandas
🔢 numpy
📊 matplotlib
🌊🐦 seaborn
🧠 scikit-learn

### 🖥️ Environment Setup
It's highly recommended to use a virtual environment for your projects. 

- first clone the repo
```
  # clone repo
git clone https://github.com/lamelkekana/Obesity_Prediction.git
```
You can use Python’s built-in venv module to create a virtual environment

**Create the new evironment**

```
# create enironment
python -m venv <env_name>
# activate environment
obesity_env\Scripts\activate

```
**If pip is not installed in your environment, you can install it by running:**

```
python -m ensurepip --upgrade
```
**Install the Project Dependencies**
```
pip install -r requirements.txt

```
Aternatively ,you can use use conda to create environment,this is applicable if you have anaconda installed in your machine

**Create the new evironment** -

```
 # create the conda environment
conda create --name <env>
```

**This is how you activate the virtual environment in a terminal and install the project dependencies**

```
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project, requirements.txt is provided in the the repo
pip install -r requirements.txt ```
```

### 📂 Opening the Jupyter Notebook File

Make sure the environment is activated as per instruction above

```

# change directory to the path to your cloned repo
cd <repository_folder>

# Launch notebook
jupyter notebook

```

### 📝 License

Obesity Prediction Dataset, Fabio Mendoza Palechor, Alexis De la Hoz Manotas, 2019, license: CC BY 4.0
