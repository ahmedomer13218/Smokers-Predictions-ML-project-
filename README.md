
# Smoker Prediction
This project focuses on building a Smoker Prediction model  using classical machine learning techniques. The system predicts if the person is smoker or not based on biological signals.

## Table of Contents
- Overview
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
The Modes utilizes both classical and advanced machine learning models to Predict if the person is smoker or not  based on some biological signals. We developed Over 600 combination or different data Preprocessing and modeling  using Automated Piplines . The  dataset I used for training and evaluation was Smoker Status Prediction using Bio-Signals on kaggle .
dataset link : https://www.kaggle.com/datasets/gauravduttakiit/smoker-status-prediction-using-biosignals

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
- Sampling , Transformation , Scaling , Dimentionality Reduction : I Used several " over 600 " Piplines to Preprocess the data "look at  [Smokers_Prediction.ipynb](./Smokers_Prediction.ipynb)"

### Modeling
- Models : LogisticRegression , RandomForestClassifier , DecisionTreeClassifier , SVC(linear,poly,RBF) ,KNeighborsClassifier ,XGBClassifier,GradientBoostingClassifier,CatBoostingClassifier ,AdaBoostingClassifier , HistgradBoostingClassifier 
I have combine this models to the Preprocessing Piplines

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
