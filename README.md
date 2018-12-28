# Breast Cancer Prediction using SVM
List of packages that are required to be installed before running the code:
NUMPY  #for dataset handling
PANDAS  #for dataset handling
MATPLOTLIB #for resizing the plot
SEABORN  #for plotting heatmaps, scatterplot
SCIKIT_LEARN #for modelling and breast cancer dataset

The dataset description file is already there.
initially we try to know the dataset.


The keys of datasets are 'data', 'target', 'target_names', 'DESCR', 'feature_names'
The # feature_names that are the features of datasets which is 30 in count and listed as follows


'mean radius' 'mean texture' 'mean perimeter' 'mean area'
'mean smoothness' 'mean compactness' 'mean concavity'
'mean concave points' 'mean symmetry' 'mean fractal dimension'
'radius error' 'texture error' 'perimeter error' 'area error'
'smoothness error' 'compactness error' 'concavity error'
'concave points error' 'symmetry error' 'fractal dimension error'
'worst radius' 'worst texture' 'worst perimeter' 'worst area'
'worst smoothness' 'worst compactness' 'worst concavity'
'worst concave points' 'worst symmetry' 'worst fractal dimension'
 
The Target_names are the target variable of dataset that are 'malignant','benign' which is the type of breast cancer.
Malignant tumors grows rapidly while benign is slow growing tumor. In simple words, we can say that the malignant tumor
is very dangerous.

So our work is prepare a model that can able to predict that the patient is suffering from which type of tumor or
we can say that we need to classify the given patients into two categories i.e MALIGNANT and BENIGN.

The dimension of dataset is 569 rows and 30 columns

Correlation matrix is plotted to know which variable having more impact on target so among all the variable for 
this study we are considering only these variables: mean radius","mean texture","mean area","mean perimeter","mean smoothness"


The Support Vector Machine Classifier is used to classify the patients.

The confusion matrix is showing the accuracy of model.


Thank you

