# Iris_Flower_Classification
## Overview
This project analyzes the classic **Iris Flower Dataset**, which consists of 150 entries with four features:
- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**
- **Class Label (Species)**

The dataset contains three different species:
- *Iris-setosa*
- *Iris-virginica*
- *Iris-versicolor*

## Dataset Source
The dataset used in this project was obtained from **Kaggle**.

## Project Workflow
1. **Data Loading & Exploration**:
   - Read the dataset using pandas.
   - Visualize the relationships using Seaborn pair plots.
2. **Data Preprocessing**:
   - Split the dataset into features (**X**) and labels (**Y**).
   - Divide data into training and testing sets.
3. **Model Training & Evaluation**:
   - **Support Vector Classifier (SVC)**
   - **Logistic Regression**
   - **Decision Tree Classifier**
   - **Random Forest Classifier**
   
Each model is trained and tested, and their accuracy is compared.
4. **Model Performance Report**:
   - Generate classification reports for all models.

## Dependencies
Ensure you have the following libraries installed:
```bash
pip install pandas numpy seaborn scikit-learn matplotlib
```

## Installation & Usage
1. Clone this repository:
```bash
git clone https://github.com/your-username/iris-flower-classification.git
cd iris-flower-classification
```
2. Run the Python script:
```bash
python iris_analysis.py
```

## Results
Each model was evaluated based on accuracy. The classification report for each model is displayed after execution.

## Visualization
We use Seaborn to generate pair plots to visualize the dataset:
```python
sns.pairplot(df, hue='Class_label')
plt.show()
```



