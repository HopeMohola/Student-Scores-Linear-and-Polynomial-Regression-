# Student Scores Linear and Polynomial Regression Analysis

## Overview

- This project explores the relationship between the duration of an exam and the scores achieved by students using linear regression.

## Objective

- The goal of this analysis is to determine whether there is a statistically significant correlation between the amount of time spent on an exam and the score achieved. This insight can help improve future exam design and study strategies.

## Dataset

- Number of Entries: 60

- Score Range: 36 to 65

- Exam Time Range: 1.1 to 9.2 hours

- Average Score: 46.43

- Average Exam Duration: 5.15 hours

- Outlier Observed: A score of 65


## Analysis & Findings

- The distribution of exam duration is right-skewed.

- Mean Squared Error (MSE): 15.67

- Root Mean Squared Error (RMSE): 3.96

- R² Score: 0.58 (model explains over half of the variability in scores).


## Dependencies

To run this notebook, install the following dependencies:

- pip install numpy pandas matplotlib seaborn scikit-learn

Running the Notebook

Clone the repository:

- git clone <repository-url>

Navigate to the project directory:

-cd student-scores-analysis

Open the Jupyter Notebook:

- jupyter notebook "Student Scores Analysis.ipynb"

Run all cells to see the results.


## Conclusion

The study shows a moderate correlation between exam duration and scores. While exam time is a factor, other variables may influence student performance.


Contributing

Feel free to submit issues or pull requests for improvements.

Acknowledgments

Thanks to the open-source community and educational researchers for inspiration in this analysis.

Side Note: I've also done Polynomial Regression to see if there was an improvement and indeed there was. You could use other models if you want to for improvement.
