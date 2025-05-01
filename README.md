# Exploratory-Data-Analysis-EDA-on-Titanic-Datasets

🧪 Exploratory Data Analysis: Titanic Dataset
📌 Objective
The goal of this task was to explore the Titanic dataset using statistical and visual methods to uncover patterns, trends, and anomalies that could influence survival.

🔧 Tools Used
Python

Pandas

Matplotlib

Seaborn

📊 Key Steps
Loaded the dataset and checked structure with .info() and .describe().

Handled missing values and explored class distributions with .value_counts().

Visualized numerical distributions using histograms and boxplots.

Explored relationships via:

sns.pairplot() for pairwise feature analysis

sns.heatmap() for correlation matrix

sns.countplot() for survival by gender and class

🔍 Insights
Gender Impact: Female passengers had a much higher survival rate than males.

Class Influence: Passengers in 1st class were more likely to survive compared to those in 3rd class.

Fare and Age: Fare was positively skewed with several high-value outliers; younger passengers had slightly higher survival.

Correlation: Moderate correlation observed between Fare and Pclass.

📁 Deliverables
titanic_eda.ipynb – Jupyter Notebook with code and visualizations

titanic_eda.pdf – PDF report with visuals and observations

✅ Outcome
This analysis helped develop skills in:

Statistical summarization

Data visualization

Pattern recognition

Understanding data-driven storytelling
