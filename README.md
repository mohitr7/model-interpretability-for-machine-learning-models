# Model Interpretability

- We have often found that **Machine Learning (ML)** algorithms capable of capturing **structural non-linearities** in training data - models that are sometimes referred to as **'black box' (e.g. Random Forests, Deep Neural Networks, etc.)** - perform far **better at prediction** than their **linear counterparts (e.g. Generalized Linear Models)**. 


- They are, however, much **harder to interpret** - in fact, quite often it is **not possible to gain any insight into why a particular prediction has been produced**, when given an **instance of input data (i.e. the model features)**. 


- Consequently, it has **not been possible to use 'black box' ML algorithms** in situations where clients have sought **cause-and-effect explanations for model predictions**, with end-results being that sub-optimal predictive models have been used in their place, as their explanatory power has been more valuable, in relative terms.


- The **problem with model explainability** is that it’s **very hard to define a model’s decision boundary in human understandable manner**. 


- Here, I’m using **[LIME](https://github.com/marcotcr/lime)** and **[SHAP](https://github.com/slundberg/shap)** to **interpret** **RandomForest model** for both classification and regression problems.

<br>

## [LIME](https://github.com/marcotcr/lime)


- **[LIME](https://github.com/marcotcr/lime)** is a **python library** which tries to **solve for model interpretability by producing locally faithful explanations**. 

<br><br> 
![](images/lime.jpg)

<br>

### [Model Interpretability using LIME](https://github.com/mohitr7/model-interpretability-for-machine-learning-models/tree/master/lime)

- **LIME** stands for **Local Interpretable Model-Agnostic Explanations** is a technique to **explain the predictions of any machine learning classifier**, and **evaluate its usefulness** in various **tasks** related to **trust**.

<br>

## [SHAP](https://github.com/slundberg/shap)


- **[SHAP](https://github.com/slundberg/shap) (SHapley Additive exPlanations)** is a unified approach to **explain the output of any machine learning model**.

<br><br> 
![](images/shap.png)

<br>

### [Model Interpretability using SHAP](https://github.com/mohitr7/model-interpretability-for-machine-learning-models/tree/master/shap)

- **SHAP connects game theory with local explanations**, uniting several previous methods and representing the only possible consistent and locally accurate additive feature attribution method based on expectations.

<br>

## Folder Heirarchy

- [**data**](https://github.com/mohitr7/model-interpretability-for-machine-learning-models/tree/master/data) folder contains the **dataset** used in the **classification** and **regression models**.

  - [**Boston.csv**](https://github.com/mohitr7/model-interpretability-for-machine-learning-models/blob/master/data/Boston.csv) is **used for regression** models. This dataset was taken from [**UCI Machine Learning Repository**](https://archive.ics.uci.edu/ml/index.php) from this [**link**](https://archive.ics.uci.edu/ml/datasets/Housing).
  
  - [**mushrooms.csv**](https://github.com/mohitr7/model-interpretability-for-machine-learning-models/blob/master/data/mushrooms.csv) is **used for classification** models. This dataset was taken from [**UCI Machine Learning Repository**](https://archive.ics.uci.edu/ml/index.php) from this [**link**](https://archive.ics.uci.edu/ml/datasets/Mushroom).
  
  
- [**lime**](https://github.com/mohitr7/model-interpretability-for-machine-learning-models/tree/master/lime)

  - [**classification**](https://github.com/mohitr7/model-interpretability-for-machine-learning-models/tree/master/lime/classification): This **folder contains** the [**notebook**](https://nbviewer.jupyter.org/github/mohitr7/model-interpretability-for-machine-learning-models/blob/master/lime/classification/LIME%20on%20Random%20Forest%20%28Classification%29.ipynb) with **classification dataset**.
  
  - [**regression**](https://github.com/mohitr7/model-interpretability-for-machine-learning-models/tree/master/lime/regression): This **folder contains** the [**notebook**](https://nbviewer.jupyter.org/github/mohitr7/model-interpretability-for-machine-learning-models/blob/master/lime/regression/LIME%20on%20Random%20Forest%20%28Regression%29.ipynb) with **regression dataset**.


- [**shap**](https://github.com/mohitr7/model-interpretability-for-machine-learning-models/tree/master/shap)

  - [**classification**](https://github.com/mohitr7/model-interpretability-for-machine-learning-models/tree/master/shap/classification): This **folder contains** the [**notebook**](https://nbviewer.jupyter.org/github/mohitr7/model-interpretability-for-machine-learning-models/blob/master/shap/classification/SHAP%20on%20Random%20Forest%20%28Classification%29.ipynb) with **classification dataset**.
  
  - [**regression**](https://github.com/mohitr7/model-interpretability-for-machine-learning-models/tree/master/shap/regression): This **folder contains** the [**notebook**](https://nbviewer.jupyter.org/github/mohitr7/model-interpretability-for-machine-learning-models/blob/master/shap/regression/SHAP%20on%20Random%20Forest%20%28Regression%29.ipynb) with **regression dataset**.
  
 <br>
 
 - If the **notebooks don't render** in **github**, **ope**n them **using** [**nbviewer**](https://nbviewer.jupyter.org/).
 
   - **Open** the **notebook in github**.
   
   - **Copy** the **page URL**.
   
   - **Paste** the **URL in** [**nbviewer**](https://nbviewer.jupyter.org/).
   
   - **Click** on **Go**. Notebook will open in [**nbviewer**](https://nbviewer.jupyter.org/).
