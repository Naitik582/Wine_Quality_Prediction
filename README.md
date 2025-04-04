<h1>Wine Quality Prediction</h1>

**Project Description**

• This project focuses on predicting the quality of wine based on its chemical characteristics. Different machine learning models are used to analyze features like acidity and density to determine wine quality. The dataset consists of multiple chemical attributes that influence the final classification.

**Dataset**

• The dataset contains various chemical properties of wine, such as:

**Fixed acidity**

• Volatile acidity

• Citric acid

• Residual sugar

• Chlorides

• Free sulfur dioxide

• Total sulfur dioxide

• Density

• pH

• Sulphates

• Alcohol

• Quality (Target Variable)


**Libraries Used**

• Pandas – For data manipulation and preprocessing

• NumPy – For numerical operations

• Matplotlib & Seaborn – For data visualization

• Scikit-learn – For machine learning models and evaluation


**Project Workflow**

**1. Data Exploration:**

• Load the dataset using Pandas

• Check for missing values and data distribution

• Analyze correlations between features



**2. Data Preprocessing:**

• Handle missing values (if any)

• Feature scaling and normalization

• Splitting data into training and testing sets



**3. Model Training & Evaluation:**

• Implemented three classifier models:

• Random Forest Classifier

• Stochastic Gradient Descent (SGD)

**Support Vector Classifier (SVC)**


**Evaluated models using accuracy, precision, recall, and confusion matrix**



**4. Prediction & Results:**

• Compared model performance

• Selected the best-performing model for wine quality prediction




**Results**

• The models were trained and tested on the dataset.

• Random Forest and SVC provided better accuracy compared to SGD.

• Visualizations helped in understanding feature importance.


**How to Run the Project**

1. Clone the repository

git clone <repo-link>


2. Install required libraries

pip install pandas numpy matplotlib seaborn scikit-learn


3. Run the script

python wine_quality_prediction.py



**Conclusion**

• This project demonstrates how machine learning can be applied to classify wine quality based on chemical properties. It highlights data preprocessing, visualization, and model evaluation techniques used for classification tasks.

