W1D1 — NumPy Fundamentals

Objective

Use NumPy to load a real CSV dataset and calculate basic statistics such as mean, standard deviation, and correlation.

Project Files

W1D1/
├── student_scores.csv
├── numpy_statistics.py
└── README.md

Requirements

Python 3.x

NumPy

Install NumPy:

pip install numpy

Dataset

The project uses student_scores.csv, which contains:

Hours_Studied — number of hours studied

Exam_Score — exam score

Example:

Hours_Studied,Exam_Score
2,55
3,60
4,65
5,70
6,75
7,80
8,85
9,90
10,95

Code

numpy_statistics.py loads the CSV using NumPy and calculates:

Mean using np.mean()

Standard deviation using np.std()

Correlation using np.corrcoef()

No Python loops are used for the calculations.

Run the Program

Open a terminal in the project folder and run:

python numpy_statistics.py

Expected Output

NumPy Statistics
----------------
Mean Hours Studied: 6.00
Mean Exam Score: 75.00
Std Hours Studied: 2.58
Std Exam Score: 12.91
Correlation: 1.00

Concepts Practiced

NumPy arrays

Loading CSV data

Array slicing

Mean

Standard deviation

Correlation

Vectorised NumPy operations

Git Commit

Required commit message:

git add .
git commit -m "feat: numpy fundamentals — array ops and statistics"

Learning Outcome

After completing this task, I can use NumPy to load numerical data from a CSV file and perform basic statistical analysis efficiently without using Python loops.
