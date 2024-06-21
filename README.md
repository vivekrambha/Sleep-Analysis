Introduction
The focus of this research is to identify how various health and lifestyle factors influence sleep. By analyzing these patterns, we hope to provide insights that encourage healthier sleep and lifestyle choices.

Dataset
The dataset includes 12 variables related to individuals' sleeping habits and activities. These variables encompass:

Demographics: Gender, Age Group
Lifestyle Factors: Physical Activity Level, Stress Levels, Overall Activeness, Occupation
Sleep Metrics: Sleep Quality, Sleep Duration
Health Data: Heart Rate, BMI, Blood Pressure
The dataset has been categorized for better analysis and is suitable for structure learning to identify patterns and relationships between the variables.

Dataset Source: Kaggle Sleep Health and Lifestyle Dataset

Analysis
The analysis involved creating a Directed Acyclic Graph (DAG) to depict how various health and lifestyle factors collectively influence sleep. The following algorithms were used for structure learning:

Hill Climbing (HC)
TABU
SaiyanH
MAHC
Greedy Equivalence Search (GES)
Metrics such as Log-Likelihood (LL), Bayesian Information Criterion (BIC), Structural Hamming Distance (SHD), and F1 scores were used to evaluate the performance of these algorithms.

Results
The analysis revealed various insights:

Physical Activity: More active individuals tend to have healthier heart rates, better sleep, and lower risk of sleep disorders.
Occupation and Stress: Occupation-related stress impacts sleep quality, potentially contributing to sleep disorders.
BMI and Blood Pressure: Higher BMI can influence blood pressure, which is linked to sleep quality.
The algorithms' performance varied, with the MAHC algorithm showing the highest F1 score, indicating its effectiveness in identifying true relationships within the data.

Summary of Results
Algorithm	Log-Likelihood	BIC Score	F1 Score
HC	-3291.824	-4496.936	0.133
TABU	-3291.824	-4496.936	0.133
SaiyanH	-3206.532	-4445.832	0.118
MAHC	-3589.812	-4547.064	0.138
GES	-3291.824	-4496.936	0.133
