🎓 Student Performance Data Analysis

A comprehensive data analysis project focused on understanding and predicting student academic performance using machine learning and visualization techniques. This project explores various factors like gender, parental education, lunch type, and test preparation in relation to student scores.

---

📌 Table of Contents

- Project Overview
- Features
- Dataset
- Tech Stack
- Installation
- Usage
- Project Structure
- Visualizations
- License

---

📖 Project Overview

This project analyzes the Student Performance Dataset from Kaggle/UCI to:
- Identify key patterns in student scores (math, reading, writing)
- Explore how socio-economic factors impact performance
- Predict student scores using regression and classification models
- Visualize insights to support education-based decision-making

---

✅ Features

- Exploratory Data Analysis (EDA)
- Visualizations with Seaborn & Matplotlib
- Predictive Modeling using:
  - Linear Regression
  - Random Forest
  - Decision Tree
- Data Cleaning & Preprocessing
- Performance Evaluation: Accuracy, MAE, RMSE
- Report Generation (Jupyter Notebook / PDF)

---

📂 Dataset

- Name: Student Performance Dataset
- Source: https://www.kaggle.com/datasets/spscientist/students-performance-in-exams
- Size: ~1,000 rows, 8 columns
- Columns:
  - Gender
  - Race/ethnicity
  - Parental level of education
  - Lunch
  - Test preparation course
  - Math score
  - Reading score
  - Writing score

---

🧰 Tech Stack

- Language: Python 3.x
- Libraries:
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn
  - Jupyter Notebook

---

💻 Installation

Clone the repository:

git clone https://github.com/yourusername/Student_Performance_Analysis.git
cd Student_Performance_Analysis

cpp
Copy
Edit

(Optional) Create a virtual environment:

python -m venv venv
source venv/bin/activate # For Windows: venv\Scripts\activate

yaml
Copy
Edit

Install dependencies:

pip install -r requirements.txt

mathematica
Copy
Edit

---

🚀 Usage

1. Launch Jupyter Notebook:

jupyter notebook

markdown
Copy
Edit

2. Open `student_performance_analysis.ipynb`
3. Run each cell to see:
   - Data cleaning
   - EDA visuals
   - ML models
   - Predictions and evaluation

---

🗂️ Project Structure

Student_Performance_Analysis/
├── data/
│ └── StudentsPerformance.csv
├── student_performance_analysis.ipynb
├── model/
├── assets/
├── requirements.txt
└── README.md

csharp
Copy
Edit

---

📊 Visualizations

Some of the key insights generated include:

- Distribution of Scores by gender and parental education
- Impact of Lunch Type on performance
- Correlation Matrix of math, reading, and writing scores
- Prediction Errors using regression models

![Sample Chart](assets/sample_score_plot.png)

---

🔮 Model Evaluation

| Model             | MAE   | RMSE  | R² Score |
|------------------|-------|-------|----------|
| Linear Regression| 5.2   | 6.3   | 0.89     |
| Random Forest    | 4.1   | 5.5   | 0.92     |

---

📜 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

🙋‍♂️ Author

Adarsh Thakur  
📧 thakuradarsh8368@gmail.com  
🔗 https://github.com/Adarshthakur-850
