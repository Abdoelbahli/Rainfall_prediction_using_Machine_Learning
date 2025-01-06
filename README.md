# **Rainfall Prediction Using Machine Learning**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0.2-green)
![Pandas](https://img.shields.io/badge/Pandas-1.3.4-orange)
![NumPy](https://img.shields.io/badge/NumPy-1.21.4-yellow)

This project focuses on predicting whether it will rain the following day using **Machine Learning** techniques. The dataset used is from the **Australian Government's Bureau of Meteorology**, and the project involves data preprocessing, model training, and evaluation using various algorithms.

---

## **Project Overview**

The goal of this project is to build and evaluate **classification models** to predict rainfall (`RainTomorrow`) based on weather data. The following machine learning algorithms are implemented and compared:

1. **Linear Regression** (Baseline)
2. **K-Nearest Neighbors (KNN)**
3. **Decision Trees**
4. **Logistic Regression**
5. **Support Vector Machine (SVM)**

The models are evaluated using metrics such as **Accuracy Score**, **Jaccard Index**, **F1-Score**, **LogLoss**, **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R2-Score**.

---

## **Dataset**

The dataset contains weather observations from **2008 to 2017** and includes features such as:

- **Temperature** (MinTemp, MaxTemp)
- **Rainfall**
- **Humidity**
- **Wind Speed and Direction**
- **Pressure**
- **Cloud Cover**
- **RainToday** (Binary: Yes/No)
- **RainTomorrow** (Target Variable: Yes/No)

The dataset is preprocessed to handle missing values, encode categorical variables, and normalize numerical features.

---

## **Technologies Used**

- **Python 3.8+**
- **Pandas** for data manipulation
- **Scikit-learn** for machine learning algorithms
- **NumPy** for numerical computations
- **Matplotlib/Seaborn** for data visualization (optional)

---

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rainfall-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd rainfall-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Usage**

1. Run the Jupyter Notebook:
   ```bash
   jupyter notebook ML0101EN_SkillUp_FinalAssignment.ipynb
   ```
2. Follow the steps in the notebook to:
   - Preprocess the data
   - Train and evaluate machine learning models
   - Generate performance metrics

---

## **Results**

The performance of the models is summarized below:

| Model               | Accuracy | Jaccard Index | F1-Score | LogLoss |
|---------------------|----------|---------------|----------|---------|
| Linear Regression   | 0.82     | -             | -        | -       |
| KNN                 | 0.85     | 0.45          | 0.62     | -       |
| Decision Tree       | 0.87     | 0.50          | 0.67     | -       |
| Logistic Regression | 0.88     | 0.52          | 0.68     | 0.35    |
| SVM                 | 0.86     | 0.48          | 0.65     | -       |

---

## **Contributing**

Contributions are welcome! If you'd like to improve this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

---

## **License**

This project is licensed under **© IBM Corporation 2020**.

---

## **Acknowledgments**

- **IBM** and **Coursera** for providing the course and dataset.
- The open-source community for their invaluable tools and libraries.
