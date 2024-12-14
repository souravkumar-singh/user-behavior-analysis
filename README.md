# Project Title: User Behavior Analysis and Cooking Session Insights

## Overview
This project focuses on analyzing user behavior and cooking session data to uncover actionable insights. It involves cleaning, merging, and analyzing datasets using Python and visualizing the results to support business decision-making.

### Key Objectives:
1. Analyze the relationship between cooking sessions and user orders.
2. Identify popular dishes.
3. Understand demographic factors that influence user behavior.
4. Derive actionable insights from user order trends.

## Tools and Technologies
- **Platform:** Google Colab
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, datetime
- **File:** Assignment.xlsx (Dataset for analysis)

## Dataset
### `Assignment.xlsx`
The dataset includes three sheets:
1. **UserDetails**: Contains user information (e.g., Age, Location, Favorite Meal).
2. **CookingSessions**: Includes details of cooking sessions (e.g., Session Ratings, Duration).
3. **OrderDetails**: Contains data on user orders (e.g., Dish Name, Order Date).

## Project Workflow
### 1. Data Preprocessing
- Load data from `Assignment.xlsx`.
- Handle missing values and clean the data.
- Merge datasets to create a comprehensive analysis-ready dataset.

### 2. Data Analysis
- Perform exploratory data analysis (EDA) on:
  - User demographics (e.g., Age Distribution, Location).
  - Popular dishes and meals.
  - Correlation between session ratings and order activity.
  - Order frequency trends and age group behavior.

### 3. Feature Engineering
- Add new features like `Months Since Registration` and `Order Frequency` to enhance analysis.

### 4. Data Visualization
- Create meaningful visualizations to uncover patterns and trends.

### 5. Report Generation
- Summarize findings and provide business recommendations.

## How to Use
1. Open Google Colab and upload `Assignment.xlsx` to the working directory.
2. Copy the Python scripts provided in the notebook or scripts.
3. Run the code to perform analysis and generate visualizations.

## Visualizations
Key plots include:
- Age distribution.
- Total orders by age group.
- Popular dishes.
- Relationship between session ratings and order counts.

## Insights and Recommendations
- **Target Audience:** Focus marketing efforts on specific age groups and locations.
- **Session Quality:** Enhance cooking session quality to boost order activity.
- **Menu Optimization:** Prioritize popular dishes and meals.
- **Customer Segmentation:** Leverage `Order Frequency` for personalized campaigns.

## File Upload Instructions
1. Ensure `Assignment.xlsx` is present in the working directory of Google Colab.
2. Use the following code snippet to upload files if necessary:

```python
from google.colab import files
uploaded = files.upload()
```

## Acknowledgements
- Dataset: Provided as part of the project assignment.
- Tools: Google Colab, Python.