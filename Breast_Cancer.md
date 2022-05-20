FinalProject_050322

Topic and Reason

Breast Cancer Data diagnostic dataset

Reason: 

Cancer is the second leading cause of death worldwide.According to Breastcancer.org Women in the U.S., breast cancer death rates are higher than those for any other cancer, besides lung cancer.
  a. About 1 in 8 U.S. women (about 13%) will develop invasive breast cancer over the course of her lifetime.
  b. In 2022, an estimated 287,850 new cases of invasive breast cancer are expected to be diagnosed in women in the U.S., along with 51,400 new cases of non-invasive (in situ) breast cancer.
  c. About 2,710 new cases of invasive breast cancer are expected to be diagnosed in men in 2022. A man’s lifetime risk of breast cancer is about 1 in 833.
  d. About 43,250 women in the U.S. are expected to die in 2022 from breast cancer. Death rates have been steady in women under 50 since 2007, but have continued to drop in women over 50. The overall death rate from breast cancer decreased by 1% per year from 2013 to 2018. These decreases are thought to be the result of treatment advances and earlier detection through screening.

Breast Cancer Wisconsin Diagnostic Data Set

This dataset from Kaggle shows the Wisconsin breast cancer diagnostic data set for predictive analysis

Which features have the greatest impact on breast cancer diagnosis.

Communication Protocols

Indiviual weekly tasks assigned each Tuesday during regular class hours.
Datasets maintained, cleaned, and stored as a group in the main branch.
Dastaset updates performed in class hours.
Group decides final workable dataset for the week.
Dataset editing can only occur inside indiviual scripts and related to the requirements of that assignment.
Changes to the main dataset must be communicated and agreed to by all members before change can be implemented.
Each member maintains individual git branch related to their assignment.
Individual Branches contain scripting, schema, etc related to their assignments.
Main communication about strategy and workability between tasks to be performed during Class Hours
Saturday Zoom meetings 11 AM to review challenges and coordinate approval of assignments to main branch.
All inter meeting communication to be held via Slack channel _0fp-kavita-josh-khadijah-rhian
All members approve main branch changes and README prior to Sunday submissions.
SQL Mockup Data Flow

Database will be created and housed in PostgreSQL via pgAdmin.

Within the database the following tables will be included:

Cancer death rates organized by types and country
Sustainability statistics organized by Country
Sustainability statistics joined with Cancer death rates (joined on country and year)—this will be the “working” table used primarily in the analyses
There may be additional tables generated based on further data analyses
Machine learning models will be connected to SQL database in Jupyter notebook importing the following libraries: sqlalchemy & psycopg2.

The final cleaned & analyzed data will be exported as CSV files to be then utilized in Tableau for visualizations as deemed appropriate by group.

ML Mockup and Data Flow

Explore Clean Data: a. Descriptive Statistics: Count, Mean, Std, min, 25%, median, 75%, max
Plot Data: a.Histograms to check normality and distribution
Create a Training and Test Set of Data a. accuracy, recall, F1 score and precision. c. The F1 score will be used to measure the model’s accuracy and it’s a mean of precision and recall. F1 scores closer to 1 indicate lower false positives and lower false negatives The recall score measures the extent to which the model can correctly identify true positives. The accuracy score is the relationship between the number of correct predictions and total number of predictions. The precision score represents the relationship between the true positives and all positives. d. Determine optimal number of features to be included.
Model Classification: a. Build classification models to evaluate performance on the training data b. Supervised ML Models: random forest, decision trees, logistic regression, random forest, support vector mechanisms. c. Unsupervised ML Models: clustering, PCA c. These machine learning algorithms were chosen because of they are robust to outliers and non-linear data, run efficiently on large data sets, robust against overfitting and consistent with the ML algorithms used in biomedical research.
Tableau

Final result Dahsboard and visualization anticipated to be performed with Tableau. Tableau will either link directly to the postgresSQL database or csv outputs from jupyter notebook ML project.