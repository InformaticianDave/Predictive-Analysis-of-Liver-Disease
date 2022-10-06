# Predictive-Analysis-of-Liver-Disease
Background

Due to excessive alcohol consumption, inhalation of toxic gases, ingestion of contaminated food, pickles, and medications, the number of patients with liver disease has been steadily rising. This dataset was utilized to assess prediction algorithms in an effort to alleviate the workload of physicians.

Material

This dataset consists of 416 liver patient records and 167 non-liver patient records gathered from the North East of Andhra Pradesh, India. The "Dataset" column is a class label used to distinguish between liver patient (liver disease) and non-liver patient groups (no disease). This data collection comprises 441 male patient records and 142 female medical records.

Any patient whose age is more than 89 is reported as "90."



Columns:

Age of the individual

Gender of the affected patient

Total Bilirubin

Direct Bilirubin

Alkaline Phosphotase

Alamine Aminotransferase

Aspartate Aminotransferase

Absolute Proteins

Albumin

Ratio of Albumin and Globulin

Dataset: field used for data partitioning (patient with liver disease, or no disease)

Results:

LogisticRegrsssion: 70.86%

MLP Classifier: 65.71%

RandomForestClassifier: 71.43%

GaussianNB: 56.57%

KNeighborsClassifier: 61.14%

Decision Tree Classifier: 68.00%

Support Vector Machine: 68.57%

SGDC Classifier: 59.43%
