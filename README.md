
# Smoker Prediction
This project focuses on building a Smoker Prediction model  using classical machine learning techniques. The system predicts if the person is smoker or not based on biological signals.

## Table of Contents
- Overview
- What's New
- Features
- Project Structure
- Data
- Modeling
- Installation
- Usage
- Future Work
- Contributing
- License

### Overview
The Modes utilizes both classical and advanced machine learning models to Predict if the person is smoker or not  based on some biological signals. We developed Over 250 combination or different data Preprocessing and modeling  using Automated Piplines . The  dataset I used for training and evaluation was Smoker Status Prediction using Bio-Signals on kaggle .
dataset link : https://www.kaggle.com/datasets/gauravduttakiit/smoker-status-prediction-using-biosignals

### What's New
In this project, we started with a brute force combination technique, testing over 250+ unique combinations of data preprocessing and modeling with default parameters. Each combination was saved with evaluation metrics such as ROC, Accuracy, F1 score, and F-beta score.

#### Additional Techniques Used:
- Feature Selection Filter Methods were applied to reduce model complexity:
  - Using Subsamples
  - Correlation, ANOVA, VIF analysis
  - Overlap analysis
  - Outlier removal
- We experimented with using only Boosting methods without any scaling, transformation, or sampling.
- We applied Optuna to get the best parameters for each model.
#### For the most promising combinations, we further optimized them using Grid Search to fine-tune hyperparameters and improve performance.
#### We also visualized the generated dataset to compare the performance of different methods at each step of preprocessing and modeling to find the optimal combination, not just the best method for each individual step.
### Features
- Predicts person Smoking status.

### Project Structure
 * [Smokers_Prediction.ipynb](./Smokers_Prediction.ipynb)
 * [LICENSE](./LICENSE)
 * [README.md](./README.md)
 * [data.csv](./data.csv)
 * [defaultParametersFinal.csv](./defaultParametersFinal.csv)
 * [defaultParameters_Xsvc.csv](./defaultParameters_Xsvc.csv)

### Data
The  dataset I used for training and evaluation was Smoker Status Prediction using Bio-Signals on kaggle .
dataset link : https://www.kaggle.com/datasets/gauravduttakiit/smoker-status-prediction-using-biosignals

### Data Preprocessing:
- Features Engineering : from the domain knowledge I get some equations for Features Crossing . 
- Anomaly Detection : checke the anomaly and drop it
- Sampling , Transformation , Scaling , Dimentionality Reduction : I Used several " over 250 " Piplines to Preprocess the data "look at  [Smokers_Prediction.ipynb](./Smokers_Prediction.ipynb)"

### Modeling
#### Models tested include:
- Logistic Regression
- RandomForestClassifier
- DecisionTreeClassifier
- SVC (linear, poly, RBF)
- KNeighborsClassifier
- XGBClassifier
- GradientBoostingClassifier
- CatBoostingClassifier
- AdaBoostingClassifier
- HistGradientBoostingClassifier

### Installation
- Clone this repository:
```bash
git clone https://github.com/ahmedomer13218/Smokers-Predictions-ML-project-

cd Smokers-Predictions-ML-project-

```

### Usage
- Run the Notebook: [Smokers_Prediction.ipynb](./Smokers_Prediction.ipynb)

### Future Work
- Streamlit app 
- Deep learning techniques

### Contributing
We welcome contributions! If you'd like to contribute, please fork the repository and make your changes. After testing, submit a pull request for review.

### License
This project is licensed under the MIT License - see the LICENSE file for details.
