# Analysis of the Relationship Between Absences and GPA Based on Tutoring Status

## Research Goal

This study explores how the relationship between the number of absences and GPA varies depending on tutoring status. The objective is to determine whether attending a tutoring center mitigates the negative impact of absences on GPA.

## 1. Introduction

Some students believe that skipping classes but attending a tutoring center does not affect their GPA. This analysis aims to clarify this assumption by examining the relationship between absences, GPA, and tutoring status. Insights from this study can help educators and students make informed decisions about attendance and tutoring.

## 2. Dataset Discussion

The dataset used is the **Students Performance Dataset** from Kaggle, downloaded on **February 10, 2025**. It contains information on **2,392 high school students**, including demographics, study habits, parental involvement, extracurricular activities, and academic performance. The key variables analyzed are:

- **Absences**: Number of school days missed.
- **GPA**: Grade Point Average.
- **Tutoring**: Whether a student attends a tutoring center (1 = Yes, 0 = No).

Since the dataset lacks information on collection methods, its representativeness may be limited.

## 3. Dataset Cleaning

- **No missing values** were found.
- **No rows were dropped**, as outliers were not detected in Absences or GPA.
- **Visualizations confirmed** the dataset was suitable for analysis without additional cleaning.

## 4. Research Findings

### Relationship Between Absences and GPA Across Tutoring Status

- **Direction**: Negative for both groups.
- **Shape**: Linear in both cases.
- **Strength**: Stronger negative correlation for students attending a tutoring center.
- **Outliers**: Present in both groups.
- **Slope**: Nearly identical for both groups.
- **Intercept**: Higher for students attending a tutoring center.

### Key Takeaway

Students who attend tutoring centers tend to have **higher GPAs** than those who do not, given the same number of absences.

## 5. Conclusion

The findings suggest that while **absences negatively impact GPA** regardless of tutoring status, students who attend tutoring centers tend to perform better academically. However, potential **confounding variables**, such as the presence of students with disabilities in each group, may influence results. Future research should consider **stratification** to account for such factors.

This analysis highlights the importance of **class attendance and tutoring support** in academic performance.
