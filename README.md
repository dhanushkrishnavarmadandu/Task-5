# Task 5: Exploratory Data Analysis (EDA) - Titanic Dataset

 Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns, trends, relationships, and potential anomalies using statistical analysis and data visualization.

Tools and Technologies Used

* Python
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

 Dataset

The project uses the **Titanic dataset (`train.csv`)**, which contains information about passengers, including:

* Passenger ID
* Survival Status
* Passenger Class
* Name
* Gender
* Age
* Number of Siblings/Spouses
* Number of Parents/Children
* Ticket Number
* Fare
* Cabin
* Port of Embarkation

Exploratory Data Analysis Performed

The following analysis was performed:

* Dataset overview using `head()` and `tail()`
* Dataset information using `info()`
* Statistical summary using `describe()`
* Missing value analysis
* Duplicate value analysis
* Value count analysis
* Survival distribution analysis
* Gender distribution analysis
* Passenger class distribution analysis
* Age distribution using histograms
* Outlier detection using boxplots
* Survival analysis based on gender
* Survival analysis based on passenger class
* Fare distribution analysis
* Scatterplot analysis
* Pairplot analysis
* Correlation analysis using a heatmap

 Visualizations Used

The project includes the following visualizations:

* Count Plots
* Histograms
* Boxplots
* Scatterplots
* Pairplots
* Correlation Heatmap

Key Findings

* The number of passengers who did not survive was higher than the number who survived.
* Female passengers generally had a higher survival rate compared to male passengers.
* Passenger class showed a relationship with survival outcomes.
* Higher-class passengers generally had better survival chances.
* The age distribution showed passengers from different age groups.
* The fare distribution was positively skewed, with some passengers paying significantly higher fares.
* Boxplots helped identify the distribution and potential outliers in numerical variables.
* The correlation heatmap helped identify relationships between numerical features.

 Project Files

```text
Task-5-Exploratory-Data-Analysis/
│
├── Task_5_EDA_Titanic.ipynb
├── Task_5_EDA_Titanic_Report.pdf
├── train.csv
└── README.md
```

How to Run the Project

1. Download or clone this repository.
2. Open the Jupyter Notebook (`.ipynb`) file using Google Colab or Jupyter Notebook.
3. Make sure the `train.csv` dataset is available.
4. Run the notebook cells sequentially.
5. Explore the visualizations and observations.

Conclusion

This Exploratory Data Analysis project helped identify meaningful patterns, trends, and relationships in the Titanic dataset. Statistical analysis and visualizations provided valuable insights into passenger characteristics and survival outcomes. The project demonstrates the importance of EDA in understanding data before performing further analysis or building machine-learning models.

---

 Author

**Dhanush Krishna Varma Dandu**
