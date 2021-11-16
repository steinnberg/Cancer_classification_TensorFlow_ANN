# Cancer_classification_TensorFlow_ANN

  This project of data science aims to study a model of cancer classification. Two categories are taken into accout. Either benign (0) or malignant(1).
The set of clean data is a complet caracterisation of a cancer through different columns of values ('mean radius', 'mean texture', 'mean perimeter', 'mean area','mean smoothness', 'mean compactness', 'mean concavity','mean concave points', 'mean symmetry', 'mean fractal dimension','radius error', 'texture error', 'perimeter error', 'area error','smoothness error', 'compactness error', 'concavity error','concave points error', 'symmetry error', 'fractal dimension error','worst radius', 'worst texture', 'worst perimeter', 'worst area','worst smoothness', 'worst compactness', 'worst concavity','worst concave points', 'worst symmetry', 'worst fractal dimension',
'benign_0__mal_1').

1) Firstly: datas are visualized through different methods: head(), describe(). countplot()

2) Feature selection is implemented to see the main important columns according to their correlation values. The methods used are df.corr() and sns.heatmap()

3) Pre-processing step is impemented through the library Scikit-learn

4) The predictif model proposed is an artificial neural network (ANN).
    - Sequential model from Keras
    - 3 layers: 1 input and 2 hidden
    -  Relu activation function
5) Confusion metric is used to quantify the precision of the model 
