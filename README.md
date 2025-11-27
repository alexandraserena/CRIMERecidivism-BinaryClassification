I built an end-to-end pipeline to find the best model capable of predicting the __recidivism__ of criminal offenders after two years from their previous charge; I performed configuration, with Sampling, Dimensionality Reduction and four different models, I combined all possible configurations and then performed __Stratified K-Fold cross-validation__ to find the best one.
The best-performing model appeared to be __GradientBoosting__, with an accuracy of approximately 71%.

The dataset contains 7214 criminal defendants from Broward County, Florida, and numerous information from which I selected the most important and relevant to predict recidivism of offence.

I selected the following __features__:

- Sex
- Race: African-American, Caucasian, Hispanic, Native American, Asian, other...
- Age
- Prior crimes count
- Current charge degree: felony or misdemeanour (F or M)
- Juvenile records: whether the defendant has juvenile records (binary: 0 or 1)
- Two years recidivism (TARGET): whether the criminal defendant has re-offended after two years from the previous offence. (binary: 0 or 1)
- The goal is to predict whether criminal defendants have committed again a crime after two years from the previous offence, therefore the task that has to be performed is a binary classification.

Source of the dataset: https://www.kaggle.com/datasets/danofer/compass


<img width="1600" height="600" alt="Copia di Testo del paragrafo" src="https://github.com/user-attachments/assets/88da10a4-65e3-459d-a5ca-385ced9e0087" />
