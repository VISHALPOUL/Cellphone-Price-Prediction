📱 Cell Phone Price Prediction – Dataset Description
📌 Overview

This dataset is designed to analyze and predict the price range of mobile phones based on their technical specifications. It is commonly used for machine learning classification tasks, where the objective is to classify mobile phones into predefined price categories using feature-based analysis.

The dataset contains numerical and categorical attributes representing hardware, connectivity, and performance-related characteristics of smartphones.

📊 Dataset Objective

The primary goal of this dataset is to:

Understand how different mobile phone features influence price

Perform exploratory data analysis (EDA)

Build and evaluate machine learning models for price classification

Apply feature selection, scaling, and model optimization techniques

🧾 Features Description

Each row in the dataset represents a single mobile phone, and the columns describe its specifications.

Feature Name	Description
battery_power	Total energy a battery can store (mAh)
blue	Bluetooth support (0 = No, 1 = Yes)
clock_speed	Speed of the microprocessor (GHz)
dual_sim	Dual SIM support (0 = No, 1 = Yes)
fc	Front camera megapixels
four_g	4G support (0 = No, 1 = Yes)
int_memory	Internal memory (GB)
m_dep	Mobile depth (cm)
mobile_wt	Weight of the mobile phone (grams)
n_cores	Number of processor cores
pc	Primary camera megapixels
px_height	Pixel resolution height
px_width	Pixel resolution width
ram	Random Access Memory (MB)
sc_h	Screen height (cm)
sc_w	Screen width (cm)
talk_time	Maximum talk time (hours)
three_g	3G support (0 = No, 1 = Yes)
touch_screen	Touch screen support (0 = No, 1 = Yes)
wifi	WiFi support (0 = No, 1 = Yes)
price_range	Target variable (0 = Low, 1 = Medium, 2 = High, 3 = Very High)
🎯 Target Variable

price_range is a multiclass label indicating the price category of the mobile phone.

This makes the problem a supervised classification task.

🛠 Use Cases

This dataset is ideal for:

Machine Learning projects

Classification algorithms (Logistic Regression, Random Forest, XGBoost, etc.)

Feature importance analysis

Data preprocessing practice

Academic submissions and GitHub portfolios

🚀 Project Workflow (Suggested)

Data Loading & Inspection

Exploratory Data Analysis (EDA)

Feature Scaling & Selection

Model Building

Model Evaluation

Result Interpretation

📁 Repository Usage

The notebook included in this repository demonstrates:

End-to-end data analysis

Model training using the provided dataset

Performance evaluation without using any external test files

✅ License

This dataset is intended for educational and research purposes.
