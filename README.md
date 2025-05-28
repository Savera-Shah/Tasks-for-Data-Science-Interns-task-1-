# Tasks-for-Data-Science-Interns-task-1-

#  EDA and Visualization of a Real-World Dataset

This repository contains the Exploratory Data Analysis (EDA) of the Titanic dataset to understand survival patterns and data trends.


## Project Steps

1. **Load Dataset**
   - Load `titanic.csv` using Pandas.

2. **Data Cleaning**
   - Filled missing values:
     - `Age`: Median
     - `Embarked`: Mode
   - Dropped `Cabin` column.
   - Removed duplicate entries.

3. **Outlier Handling**
   - Used IQR method to remove outliers from the `Fare` column.

4. **Visualizations**
   - **Bar Charts**: `Survived`, `Sex`, `Embarked`
   - **Histograms**: `Age`, `Fare`
   - **Heatmap**: Correlation between numerical features

5. **Summary of Insights**
   - Extracted meaningful observations from data.

## How to Run

1. Clone this repository:
    
   git clone https://github.com/your-username/titanic-eda.git
   cd titanic-eda
   
4. Install dependencies:

pip install pandas matplotlib seaborn

**Observations**

1. Most passengers were male and boarded at port 'S'.

2. Majority of passengers did not survive.

3. Higher Fare → higher chance of survival.

4. Age and Fare show right-skewed distributions.

5. Strong correlation between Pclass, Fare, and Survival.
