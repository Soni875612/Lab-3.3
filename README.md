## Lab Activity 3.3 — Computing and Visualizing Skewness and Kurtosis for Literacy Rate Distribution
Objective
To compute and visualize the skewness and kurtosis of literacy rate distribution across various Indian states using Python. The goal is to understand the shape, symmetry, and peakedness of the data and interpret its implications for educational development and inequality among states.

Dataset
Government of India — Literacy Rate dataset from Kaggle:
🔗 Kaggle Dataset Link

Requirements

Python with libraries: numpy, pandas, scipy, matplotlib, seaborn


Prerequisites

Basic Python programming knowledge
Familiarity with NumPy, Pandas, and visualization libraries (Matplotlib/Seaborn)
Understanding of descriptive statistics and distribution shapes
Knowledge of skewness (asymmetry) and kurtosis (peakedness) concepts


Steps
StepTask1Install required libraries2Import numpy, pandas, scipy, matplotlib, seaborn3Load the literacy rate dataset4Extract the literacy rate column from the dataset5Compute Skewness and Kurtosis6Visualize the distribution and print results

Key Concepts
Skewness (skew())
Measures the asymmetry of the data distribution.
ValueMeaningSkewness = 0Perfectly symmetrical distributionSkewness > 0Right-skewed (more low values)Skewness < 0Left-skewed (more high values)
Kurtosis (kurtosis())
Indicates whether the distribution has heavy or light tails.
ValueMeaningKurtosis ≈ 0Normal distributionKurtosis > 0Leptokurtic (heavy tails, more outliers)Kurtosis < 0Platykurtic (light tails, fewer outliers)

Visualization

Histogram with KDE curve (sns.histplot(), kde=True) to visualize literacy rate distribution
Red dashed line marking the mean literacy rate


Conclusion
Analyzing skewness and kurtosis of literacy rates helps understand how literacy levels are distributed across Indian states. Skewness reveals whether the data leans toward higher or lower values, while kurtosis shows how peaked or flat the distribution is. A high positive kurtosis means most states cluster near the mean, while negative kurtosis indicates a wider spread. This analysis helps education policymakers identify regions that need more attention and resource allocation.
