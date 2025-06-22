# 🚢 Titanic Survival Prediction Model

This project uses machine learning to predict the survival of passengers aboard the Titanic, based on features such as age, sex, fare, class, and more. The model is built using Python and scikit-learn, with data preprocessing, visualization, and classification pipelines.

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 Features & Workflow

- **Data Cleaning & Preprocessing**
  - Handling missing values
  - Encoding categorical variables using `OneHotEncoder`
  - Feature scaling using `MinMaxScaler`

- **EDA (Exploratory Data Analysis)**
  - Data visualization using Seaborn and Matplotlib
  - Correlation heatmaps and distribution plots

- **Model Building**
  - Used `Pipeline` and `ColumnTransformer` to streamline preprocessing and modeling
  - Implemented `DecisionTreeClassifier` and `RandomForestClassifier`
  - Evaluated using accuracy score

---

## 📈 Results

- Achieved good accuracy and classification performance on test data using Decision Tree and Random Forest models.
- Getting better accuracy using Random Forest model than Decision Tree.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/swarnabhaghosh/Titanic_Survival_Prediction_Model.git
   Navigate to the directory and open the notebook:
2. Navigate to the directory and open the notebook:
   ```bash
   cd Titanic_Survival_Prediction_Model
   jupyter notebook Titanic_Dataset_using_Pipeline.ipynb
3. Run each cell to see the step-by-step workflow.

## 📥 Download Dataset via KaggleHub

You can programmatically download the dataset using `kagglehub`:

  ```python
  import kagglehub
  
  # Download latest version
  path = kagglehub.dataset_download("brendan45774/test-file")

  print("Path to dataset files:", path)
  ```

## 📬 Contact
Created with ❤️ by Swarnabha Ghosh  
Feel free to reach out or contribute!  
Email: [swarnabha983@gmail.com](mailto:swarnabha983@gmail.com)
