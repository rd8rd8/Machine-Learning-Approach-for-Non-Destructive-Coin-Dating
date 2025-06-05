# Machine-Learning-Approach-for-Non-Destructive-Coin-Dating

# Data Analysis and Modeling Project

This repository contains Jupyter Notebooks and datasets used for exploratory data analysis and machine learning model training. The project focuses on understanding spectral and XRF-based measurements and predicting chemical concentrations and properties from training and testing datasets.

## 📁 Repository Contents

### 📝 Notebooks

- `EDA.ipynb`: **Exploratory Data Analysis (EDA)**
  - Inspects the datasets
  - Cleans and preprocesses the data
  - Visualizes feature distributions, relationships, and trends
  - Summarizes key insights for modeling

- `Models Training.ipynb`: **Model Training and Evaluation**
  - Merges, preprocesses, and transforms input data
  - Trains machine learning models using the training set
  - Evaluates model performance on the test set
  - Compares different models

### 📊 Data Files

- `wavex.csv`: Contains the index of wavelengths used in the reflectance measurements.
- `dados.csv`: Main training set with fields such as mass, reflectance, color, and year.
- `dados_teste.csv`: Test set corresponding to `dados.csv`, used for evaluation.
- `dados_xrf.csv`: XRF-based elemental concentrations and error estimates for the training set.
- `dados_xrf_teste.csv`: XRF-based elemental concentrations and errors for the test set.

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Machine-Learning-Approach-for-Non-Destructive-Coin-Dating.git
   cd your-repo-name
   ```

2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 🔄 Workflow

1. **EDA**: Understand dataset structure and data quality.
2. **Data Preparation**: Merge spectral and XRF data, preprocess features.
3. **Model Training**: Fit machine learning models to the training data.
4. **Evaluation**: Validate performance on the test set and interpret results.

## 📄 License

This project is open-source under the MIT License.

## 🙋‍♀️ Contact

If you have any questions or suggestions, feel free to open an issue.
