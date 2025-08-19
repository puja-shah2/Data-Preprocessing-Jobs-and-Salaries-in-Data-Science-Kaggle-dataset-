Preprocessed dataset from Kaggle, "Jobs and Salaries in Data Science," using Weka. Conducted comprehensive preprocessing to enhance dataset robustness and prepare it for analysis. Explored relationships, identified patterns, and understood factors influencing salary levels in the data science field for the year 2023.

Key Points:
- Conducted preprocessing operations including handling missing values, normalization (min-max and z-score), discretization, change of nominal attributes to binary, and data reduction using PCA.
- Addressed missing values to ensure data completeness.
- Standardized numerical features to prevent scale dominance.
- Simplified dataset through supervised discretization.
- Transformed nominal attributes into binary format to improve algorithm compatibility.
- Reduced dimensionality using PCA for improved efficiency and interpretability.

Outcome:
Preprocessing steps collectively enhanced dataset robustness, standardized it for a wide range of analytical techniques, and prepared it for in-depth analysis of data science job trends and salary determinants in 2023.

Implemented a classification model using the Weka machine learning toolkit to categorize job listings from Kaggle dataset "Jobs and Salaries in Data Science". The dataset comprised 9355 instances with attributes such as salary, experience level, employment type, and company size.

Approach:
- Used J48 decision tree classifier with parameters -C 0.25 -M 2.
- Selected attributes: salary_in_usd, experience_level, employment_type, company_size.
- Evaluated model performance using 10-fold cross-validation.

Results:
- Achieved an accuracy of 91.16%.
- Identified 35 nodes and 18 leaves in the decision tree.
- Successfully predicted medium salary jobs (Class M) with high precision (0.917) and recall (0.993).
However, struggled with low salary (Class L) and low frequency (Class S) jobs, with low recall and precision scores. Notably, no instances correctly classified for low frequency jobs.

Conclusion:
While the model performed well in predicting medium salary jobs, it faced challenges in accurately classifying low salary and low frequency jobs, possibly due to the complexity of real-world job market dynamics.
