CSC_6850-MachineLearning-AssignmentTwo
# Prediction Model Analysis
The source code is intended to demonstrate the differences specific machine learning models, and demonstrate basic machine learning principals. The project includes analysis and comparison of three prediction models used on the scikit-learn Wine dataset. 
<br>
<br>
The project was assigned as part of CSC6780 at Georgia State University. The code can be recreated by visiting the [reposity](https://github.com/jmbanda/CSC4850-Machine-Learning/blob/main/Assignment2_ML.ipynb) owned by Dr. Banda, Professor of Computer Science at Georgia State University, who assigned the project as part of Machine Learning coursework. The project can be completed in GoogleColab, or in any other jupyter notebook platform.  
## Data
The dataset was sourced from scikit-learn pre-loaded data sets, and can be found [here](https://archive.ics.uci.edu/ml/datasets/wine). The dataset consists of analysis results performed on Italian wines from the same region, but three different wineries. The attributes include variables of alcohol, malic acid, ash, alcalinity of ash, to name a few. This assignment primarily focues on the relationship between the alcohol, ash, and alcalinity of ash attributes. 

## Analysis
Three different machine learning models, perceptron, decision tree, and logistic regression, were utilized in this project. Each model prediction was analyzed and compared to its own prediction and model performance. Confusion matrices and classification reports were generated for each model. The decision tree classifier was also plotted in 2D and 3D with contours represending the prediction decision boundaries. All plots can be referenced below.


### Confusion Matricies 
![perceptron matrix](https://github.com/dgambone3/CSC_6850-MachineLearning-AssignmentTwo/blob/main/images/perceptron-matrix.png)
![decision tree matrix](https://github.com/dgambone3/CSC_6850-MachineLearning-AssignmentTwo/blob/main/images/decision-tree-matrix.png)
![logreg matrix](https://github.com/dgambone3/CSC_6850-MachineLearning-AssignmentTwo/blob/main/images/logreg-matrix.png)

### Prediction Models
![logreg plot](https://github.com/dgambone3/CSC_6850-MachineLearning-AssignmentTwo/blob/main/images/logreg-plot.png)
![decision tree plot](https://github.com/dgambone3/CSC_6850-MachineLearning-AssignmentTwo/blob/main/images/decision-tree-plot.png)
![perceptron plot](https://github.com/dgambone3/CSC_6850-MachineLearning-AssignmentTwo/blob/main/images/perceptron-model.png)


### Decision TreeClassification
![2d](https://github.com/dgambone3/CSC_6850-MachineLearning-AssignmentTwo/blob/main/images/tree-classify-2d.png)
![3d](https://github.com/dgambone3/CSC_6850-MachineLearning-AssignmentTwo/blob/main/images/tree-classify-3d.png)
