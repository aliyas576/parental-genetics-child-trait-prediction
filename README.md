# parental-genetics-child-trait-prediction
Synthetic dataset of 7,000 families simulating genetic trait  inheritance. Full EDA notebook covering 4 pillars plus feature  engineering and health risk classification using Random Forest  and Gradient Boosting. Built with Python, Pandas, Seaborn,  and Scikit-learn.

This repository contains a complete end-to-end data science project 
analyzing parental genetics and predicting child traits across 7,000 
synthetic family records.

The dataset covers 18 features including parental blood groups, eye 
color, hair color, skin tone, family disease history, and predicted 
child outcomes. Blood group inheritance follows real ABO and Rh rules. 
Child height is estimated using the parental midpoint formula with a 
gender-based offset.

The notebook follows a structured 4-pillar EDA framework covering data 
composition, distributions, relationships, and group comparisons across 
genetic traits, disease history, and health risk categories.

Three classification models are trained and evaluated including 
Logistic Regression, Random Forest, and Gradient Boosting. Feature 
importance analysis confirms that parental age and family disease 
history are the strongest predictors of child health risk.

Repository contents:
- parental_genetics_child_traits.csv — clean 7,000 row dataset
- parental-genetics-child-trait-eda-ml.ipynb — full EDA and ML notebook

Built using Python 3.12 with Pandas, NumPy, Matplotlib, 
Seaborn, and Scikit-learn. Suitable for beginners and intermediate 
data science learners interested in genetics, health classification, 
and inheritance pattern analysis.
