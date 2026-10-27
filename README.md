# PredictiveAnalysis

 A machine learning project built to analyze student attributes and predict academic performance.

---

## About the Project
Understanding the factors that influence academic success helps educators and institutions provide timely support. This project applies exploratory data analysis (EDA) and machine learning modeling techniques to predict student performance based on historical and behavioral data.

## Key Features
* **Data Preprocessing & Cleaning:** Handles missing values, encodes categorical variables, and scales numerical features.
* **Exploratory Data Analysis (EDA):** Visualizes correlations between study habits, attendance, and final grades using Python plotting libraries.
* **Predictive Modeling:** Trains and evaluates machine learning algorithms to forecast student scores accurately.
* **Evaluation Metrics:** Assesses model performance using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score.


## Tech Stack & Dependencies (`requirements.txt`)

To run this project, make sure you have the following Python libraries installed. You can save this list into a file named **`requirements.txt`**:

numpy>=1.20.0
pandas>=1.3.0
scikit-learn>=1.0.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0

## Project Strurcture
PredictiveAnalysis/
│
├── data/                  # Dataset files 
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── src/                   # Python scripts for data processing and training
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation


## Installation

python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

pip install -r requirements.txt

