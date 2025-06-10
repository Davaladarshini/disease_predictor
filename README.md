# Disease Prediction from Symptoms

This project explores the use of machine learning algorithms to predict diseases from symptoms. 

### Algorithms Explored

The following algorithms have been explored in code:

1. Naive Bayes
2. Decision Tree
3. Random Forest
4. Gradient Boosting

# Dataset

Source-1

The dataset for this problem used with the `main.py` script is downloaded from here:

https://www.kaggle.com/kaushil268/disease-prediction-using-machine-learning


This dataset has 133 total columns, 132 of them being symptoms experienced by patiend and last column in prognosis for the same.


This dataset has 3 columns:
Disease  | Count of Disease Occurrence | Symptom

You can either copy paste the whole table from here to an excel sheet or scrape it out using Beautifulsoup.

# Directory Structure

disease-prediction-from-symptoms/
├── dataset/
│   ├── training_data.csv
│   └── test_data.csv
│
├── saved_model/
│   └── [ pre-trained model files, e.g., gradient_boosting.pkl ]
│
├── main.py                # Loads Kaggle dataset, trains and saves selected model
│
└── notebook/
    ├── dataset/
    │   └── raw_data.xlsx  # Columbia dataset for notebook
    │
    └── Disease-Prediction-from-Symptoms-checkpoint.ipynb  
        # Notebook for loading Columbia dataset, training, evaluation, and inference



# Usage

Please make sure to install all dependencies before running the demo, using the following:

pip install -r requirements.txt





