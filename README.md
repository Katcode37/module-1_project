# Impact of Informal English Exposure on Exam Performance

## Project Overview
This project analyzes whether informal exposure to English media (such as movies, YouTube, and TV shows) is associated with better English exam results.

Because different exams are scored on different scales, the scores are standardized using **z-scores** so they can be compared fairly.

The analysis investigates:
- Whether students with informal English exposure perform better
- Whether the number of hours of exposure correlates with exam performance
- Whether there are meaningful differences between exposure groups

## Dataset
The dataset contains information about students and their English exam results.

Key variables include:
- **Overall exam score**
- **Informal English exposure** (Yes / No)
- **Hours per week of English media exposure**
- **Type of content consumed**

Missing values in the *Type of content* column were filled with `"No"`.

## Methods
The analysis includes several steps:

1. **Data Cleaning**
   - Handling missing values in the dataset

2. **Score Standardization**
   - Exam scores were converted to **z-scores** to make results comparable across different tests.

3. **Group Comparison**
   - Students with informal English exposure were compared to students without exposure.

4. **Correlation Analysis**
   - Pearson correlation was used to examine the relationship between:
     - hours of English media exposure
     - standardized exam scores

5. **Exposure Groups**
   Students were categorized into three groups:
   - Low exposure (≤ 2 hours/week)
   - Medium exposure (3–7 hours/week)
   - High exposure (> 7 hours/week)

## Results
The analysis suggests:

- Students with informal English exposure tend to achieve **higher standardized exam scores**.
- There is a **positive correlation** between hours of media exposure and exam performance.
- Students in the **high exposure group** show higher average scores compared to medium and low exposure groups.

## Technologies Used
- Python
- Pandas
- NumPy
- SciPy
- Jupyter Notebook

## How to Run the Project

1. Clone the repository
2. Install dependencies
3. Open the notebook
