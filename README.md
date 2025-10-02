# 🚢 Titanic Survival Prediction using Random Forest 

Predicting the survival of Titanic passengers using machine learning! This project uses a **Random Forest Classifier** to determine whether a passenger survived based on their characteristics.

---

## 🗂 Dataset

The dataset contains information for 891 passengers from the Titanic voyage. Key columns include:

- `PassengerId` – Unique ID for each passenger  
- `Survived` – Target variable (0 = No, 1 = Yes)  
- `Pclass` – Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- `Name`, `Sex`, `Age` – Personal information  
- `SibSp`, `Parch` – Family aboard  
- `Ticket`, `Fare` – Ticket details  
- `Cabin` – Cabin number (many missing values)  
- `Embarked` – Port of Embarkation (`C`, `Q`, or `S`)  

---

## 🛠 Project Workflow

1.  **Data Loading**: Load dataset from CSV file  
2.  **Data Cleaning & Preprocessing**  
   - Handle missing values (fill Age with mean, Embarked with mode, drop Cabin)  
   - Encode categorical columns (`Sex` and `Embarked`) into numbers  
3.  **Exploratory Data Analysis**: Visualize survival rates, passenger classes, gender distribution, etc.  
4.  **Feature Selection**: Remove irrelevant columns (PassengerId, Name, Ticket)  
5.  **Model Training**: Train a Random Forest classifier  
6.  **Model Evaluation**: Measure accuracy, confusion matrix, classification report on test data  

---

## 🚀 How to Run

1. Clone or download this repo  
2. Ensure Python 3.x and required libraries are installed:  
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

3. Place `train.csv` in your working directory or update path in code
4. Run the notebook/script in Google Colab or your IDE

---

## 📊 Performance

* ✅ Training Accuracy: ~98.3%
* ✅ Test Accuracy: ~84.4%
* The Random Forest model provides great accuracy and interpretability for predicting survival.

---

## 📚 Libraries Used

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

---

## 🔗 References

* [Titanic Dataset on Kaggle](https://www.kaggle.com/c/titanic/data)
* [Scikit-learn Random Forest Docs](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)

---
