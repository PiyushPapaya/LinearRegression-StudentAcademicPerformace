# Linear Regression Model on Student Academic Performance

This is a very basic Linear Regression Model trained on the [Kaggle Student Academic Performance Database](https://www.kaggle.com/datasets/emanfatima2025/student-academic-performance-trends)

---

The dataset consists of these columns:

- **student_id**: Each student in the dataset is given a unique identifier.

- **hours_studied**: The mean amount of time a student spent studying for the test.

- **sleep_hours**: Average daily sleep time (in hours), which represents a balanced lifestyle.

- **attendance_percent**: The student's percentage of all classes attended.

- **previous_scores**: The student's score from more recent tests.

- **exam_score**: The student's final exam score (target variable).

The first few rows of the table look like this:

| student_id | hours_studied | sleep_hours | attendance_percent | previous_scores | exam_score |
| ---------- | ------------- | ----------- | ------------------ | --------------- | ---------- |
| S001       | 8.0           | 8.8         | 72.1               | 45              | 30.2       |
| S002       | 1.3           | 8.6         | 60.7               | 55              | 25.0       |
| S003       | 4.0           | 8.2         | 73.7               | 86              | 35.8       |
| S004       | 3.5           | 4.8         | 95.1               | 66              | 34.0       |
| S005       | 9.1           | 6.4         | 89.8               | 71              | 40.3       |

---

The **Notebook** has the following sections:

- Import libraries
  
- Import batabase
  
- Define labels and features
  
- Splitting the database into train and test
  
- Define the model
  
- Train the model
  
- Predict results
  
- Calculate mean absolute error and R2 score
  
- Finding out the weight and bias

---

**Results:**

The analysis shows a strong positive correlation between the traget variable (exam_score) and the features **hours_studied** and **sleep_hour** and our label, with correlation coefficients **1.55** and **1.04**, respectively . Also a mild positive relationship is noted between **attendance_percent** and **previous_scores** and the defined label with coefficients **0.1** and **0.178**. The **MAE** of the model trained on this dataset is **2.4** and **R2 Score** being **0.814**, indicating a successfully trained model.

---

Notebook created and trained on [Kaggle](https://www.kaggle.com) by Piyush Nagpal
