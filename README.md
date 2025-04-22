# Student Performance Prediction

This project focuses on analyzing and predicting student academic performance using various assessment metrics such as quizzes, assignments, exams, attendance, and participation scores. The implementation is done in Python using libraries like Pandas, Seaborn, Matplotlib, and Plotly.

## Group Members
- Felix Omondi(Felixokoth7)
- Mariana Akinyi(Mariana200493)
- Toby Obidike(tobbi3176)

## 📁 Project Structure

The main analysis is performed in a Jupyter Notebook titled `Perfomance predictions.ipynb`.

## 📊 Dataset

- File: `students_grades.csv`
- Features include:
  - Attendance (%)
  - Midterm Score
  - Assignments Average
  - Quizzes Average
  - Final Exam Score
  - Participation Score
  - Projects Score
  - Total Score

## 🔍 Exploratory Data Analysis (EDA)

The notebook includes:
- Data cleaning (e.g., handling missing values)
- Summary statistics
- Visualizations:
  - Histograms for individual features
  - Correlation heatmaps
  - Scatter plots to observe feature relationships

## 🧠 Machine Learning Models

The following models are applied for performance prediction:
- Linear Regression
- Random Forest Regressor
- Decision Tree Regressor
- Model evaluation metrics (e.g., R² Score, MAE)

## 📈 Results

Each model’s prediction accuracy is compared, and visualizations are used to show actual vs. predicted student scores.

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly`
- `scikit-learn`

## 🚀 How to Run

1. Clone the repository.
2. Ensure you have Jupyter Notebook and Python installed.
3. Install the required libraries using:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook:
   ```bash
   jupyter notebook Perfomance\ predictions.ipynb
   ```

## 📌 Notes

- Ensure the dataset `students_grades.csv` is placed in the same directory as the notebook.
- This project is intended for educational and analytical purposes.
