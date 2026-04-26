# Google-Playstore-Data-Analysis
https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps
# Google Play Store Data Analysis Project 📱🔍

This project focuses on the Exploratory Data Analysis (EDA) and cleaning of a large-scale Google Play Store dataset. The analysis aims to understand app distributions, category trends, and prepare the data for further analytical insights.

## 🚀 Project Steps

The project is structured into the following key phases, as implemented in the Jupyter Notebook:

### 1. Data Import and Exploration
- Loading the dataset using `Pandas`.
- Initial discovery of the data structure using `.info()`, `.describe()`, and `.columns`.
- Understanding the scale of the dataset (2.3M+ rows).

### 2. Data Cleaning and Preprocessing
- Identification of missing values (nulls) across different features.
- Cleaning unnecessary columns such as `Developer Email`, `Scraped Time`, and others to streamline the analysis.
- Handling duplicates and inconsistent data entries.

### 3. Data Transformation
- Preparing features for analysis.
- Converting object-type columns into appropriate formats.
- Categorical grouping to prepare for visualization.

### 4. Data Analysis and Visualization
- Grouping apps by **Category** to find the most populated niches in the store.
- Visualizing distributions using `Seaborn` and `Matplotlib`.
- Analyzing app counts per category using bar plots to identify market trends.

## 🛠️ Tech Stack
- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** - `Pandas`: Data manipulation and cleaning.
  - `Seaborn` & `Matplotlib`: Data visualization.

## 📂 How to Use
1. Clone the repository.
2. Take the  data from the link above
3. Run the `Google_Playstore.ipynb` file to see the step-by-step analysis and generated plots.

