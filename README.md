# Heart Disease Prediction Project

## Overview

This project focuses on building a machine learning model to predict the likelihood of heart disease in patients. It utilizes the [UCI Heart Disease dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data) available on Kaggle. The goal is to develop a robust and interpretable model that can assist in early detection and prevention efforts.

## Dataset

The dataset used in this project is the "Heart Disease UCI" dataset, sourced from Kaggle: [https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data).

This dataset contains various features related to patient health, including:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting Electrocardiographic Results
* Maximum Heart Rate Achieved
* Exercise Induced Angina
* Oldpeak (ST depression induced by exercise relative to rest)
* Slope of the peak exercise ST segment
* Number of major vessels colored by fluoroscopy
* Thalassemia
* Target (0 = No heart disease, 1 = Heart disease)


## Getting Started

Follow these steps to set up and run the project:

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/aman2712/heart-disease-prediction.git](https://github.com/aman2712/heart-disease-prediction.git)
    cd heart-disease-prediction
    ```

2.  **Install the required Python libraries:**

    It is highly recommended to create a virtual environment before installing dependencies.

    ```bash
    # Create a virtual environment (if you haven't already)
    python -m venv env
    # Activate the virtual environment
    source env/bin/activate  # On macOS and Linux
    # env\Scripts\activate   # On Windows
    ```

    Then, install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3.  **Download the dataset (if not already included):**

    The `heart-disease.csv` file should ideally be present in the `root` directory. If not, you might need to download it manually from the Kaggle link provided above and place it in the `data/` folder.

4.  **Run the Jupyter Notebook:**

    ```bash
    jupyter notebook notebooks/end-to-end-heart-disease-classification.ipynb
    ```

    This will open the Jupyter Notebook in your web browser, where you can follow the analysis, model building process, and results.

## Project Highlights (Optional - Update based on your work)

* Exploratory Data Analysis (EDA) to understand the dataset characteristics.
* Data preprocessing and feature engineering steps.
* Implementation and evaluation of various machine learning models (e.g., Logistic Regression, Support Vector Machines, Random Forest, etc.).
* Model selection and hyperparameter tuning to achieve optimal performance.
* Model interpretation and insights into the factors contributing to heart disease prediction.
* Saving the trained model for future use.

## Contributing

Contributions to this project are welcome! If you have any suggestions, bug reports, or would like to add new features, please feel free to:

1.  Fork the repository.
2.  Create a new branch for your feature or fix.
3.  Commit your changes.
4.  Push to the branch.
5.  Submit a pull request.

## Contact

[Md Aman Khan] - [https://github.com/aman2712]
