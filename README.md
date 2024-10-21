# Remote Work and Mental Health Dataset

This dataset contains 5,000 records and 20 attributes related to remote work and its impact on mental health. It is useful for analyzing how working remotely affects employees' mental well-being, productivity, job satisfaction, and other factors. The dataset includes features like work environment, mental health conditions, job satisfaction, and more.

## Dataset Overview

- **Source**: [Kaggle - Remote Work and Mental Health](https://www.kaggle.com/datasets/waqi786/remote-work-and-mental-health)
- **Number of Records**: 5,000
- **Number of Attributes**: 20

### Attributes

Here’s a list of key attributes included in the dataset:

1. **Employee ID**: A unique identifier for each employee.
2. **Age**: The age of the employee.
3. **Gender**: The gender of the employee (Male, Female, Other).
4. **Country**: The country where the employee is located.
5. **Remote Work Frequency**: How often the employee works remotely (e.g., Never, Occasionally, Frequently, Always).
6. **Job Role**: The employee's job title or role.
7. **Mental Health Condition**: Whether the employee reports any mental health issues (Yes/No).
8. **Job Satisfaction**: A rating of job satisfaction on a scale of 1 to 10.
9. **Work-Life Balance**: A self-reported work-life balance score.
10. **Productivity Impact**: The impact of remote work on productivity (e.g., Positive, Negative, Neutral).
11. **Mental Health Support**: Whether the employee has access to mental health support (Yes/No).
12. **Stress Level**: Reported stress levels (Low, Moderate, High).
13. **Physical Health Impact**: The effect of remote work on physical health (e.g., Positive, Negative).
14. **Annual Salary**: The employee’s annual salary in their local currency.
15. **Job Tenure**: The length of time the employee has been in their current job role.
16. **Work Hours per Week**: The number of hours the employee works per week.
17. **Exercise Frequency**: How often the employee exercises (e.g., Daily, Weekly, Rarely).
18. **Sleep Quality**: A rating of sleep quality from 1 to 10.
19. **Commute Time**: Time spent commuting before remote work (in minutes).
20. **Mental Health Improvement**: Whether the employee’s mental health has improved since working remotely (Yes/No).

### Example Use Cases

This dataset can be used for:

- **Correlation Analysis**: Investigate how different factors such as job satisfaction, work-life balance, and stress levels correlate with remote work frequency and mental health conditions.
- **Predictive Modeling**: Build machine learning models to predict the impact of remote work on mental health or job satisfaction.
- **Exploratory Data Analysis (EDA)**: Perform EDA to discover patterns, trends, and insights regarding the remote work environment.
- **Visualizations**: Generate heatmaps, bar charts, and other visual representations to explore relationships between features.

## How to Use This Dataset

1. **Download the Dataset**: Download the CSV file from the [Kaggle dataset page](https://www.kaggle.com/datasets/waqi786/remote-work-and-mental-health/data).
2. **Load the Data**: Use Python’s `pandas` or similar libraries to load the dataset into your analysis environment.

```python
import pandas as pd

# Load dataset
data = pd.read_csv('remote_work_and_mental_health.csv')

# View first few rows
data.head()
```

3. **Explore the Data**: Start by checking for any missing values, data types, and general statistics.

```python
# Check for missing values
data.isnull().sum()

# Summary statistics
data.describe()
```

4. **Perform Analysis**: Create visualizations or build models to gain insights.

```python
import seaborn as sns
import matplotlib.pyplot as plt

# Example: Heatmap of correlations between numerical attributes
plt.figure(figsize=(10, 8))
sns.heatmap(data.corr(), annot=True, cmap='coolwarm')
plt.show()
```

## Dataset License

Refer to the [Kaggle dataset page](https://www.kaggle.com/datasets/waqi786/remote-work-and-mental-health/data) for licensing information.

## Contributions

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.
