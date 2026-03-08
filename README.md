
---

# Hackathon Models – Wonders of AI 2.0

This repository contains a collection of **machine learning models and synthetic datasets** developed during the **Wonders of AI 2.0 Hackathon**.

Our team **Neo** secured **5th place among 70+ teams**, where we built multiple AI models aimed at improving **student analytics, academic monitoring, and educational recommendations**.

The repository includes **five independent AI models**, each designed to solve a different problem in **education analytics and student performance monitoring**.

These models demonstrate applications of **machine learning**, **data generation**, **predictive analytics**, and **recommendation systems**.

---

# Team Information

Team Name: **Neo**

Achievement:

🏆 **5th Place – Wonders of AI 2.0 Hackathon**
Competing against **70+ teams**

---

# Repository Structure

```
Hackathon-models
│
├── model1
│   ├── create_dataset.py
│   ├── performance_model.ipynb
│   ├── student_performance2.csv
│   └── student_performance_model.pkl
│
├── model2
│   ├── create_dataset.py
│   ├── student alerts.csv
│   ├── knn_model.pkl
│   ├── model_for_alert.ipynb
│   └── scaler.pkl
│
├── model3
│   ├── create_dataset.py
│   ├── quiz.py
│   ├── tgpt_client.py
│   ├── tgpt_server.py
│   ├── quiz_client.py
│   └── quiz_server.py
│
├── model4
│   ├── create_dataset.py
│   ├── balanced_reading_behavior.csv
│   ├── model_for_doc.ipynb
│   └── random_forest_model.pkl
│
├── model5
│   ├── enhanced_student_recommendations.csv
│   ├── generated_student_recommendations.csv
│   ├── final.ipynb
│   └── recommendation_model.pkl
```

---

# Technologies Used

This project uses the following technologies:

| Technology       | Purpose                            |
| ---------------- | ---------------------------------- |
| Python           | Core programming language          |
| Scikit-learn     | Machine learning models            |
| Pandas           | Data processing                    |
| NumPy            | Numerical operations               |
| Jupyter Notebook | Model training and experimentation |

---

# Model 1 – Student Performance Prediction

This model predicts **student academic performance** based on multiple academic and extracurricular parameters.

### Input Features

| Feature                     |
| --------------------------- |
| CGPA                        |
| GPA                         |
| Average Assignment Marks    |
| Average Project Marks       |
| Attendance Percentage       |
| Class Participation Credits |
| Extracurricular Activities  |
| Achievements Credits        |
| Number of Students in Class |
| Rank in Class               |
| Certifications Count        |

### Output

Performance category of the student.

### Files

| File                          | Description                 |
| ----------------------------- | --------------------------- |
| create_dataset.py             | Generates synthetic dataset |
| performance_model.ipynb       | Model training notebook     |
| student_performance2.csv      | Dataset                     |
| student_performance_model.pkl | Trained ML model            |

### Example Use Case

Predict whether a student is:

• High performer
• Average performer
• At risk

---

# Model 2 – Student Alert Prediction System

This model predicts whether a student should receive **academic alerts** based on their academic activity.

### Input Features

| Feature               |
| --------------------- |
| CGPA                  |
| GPA                   |
| Attendance Percentage |
| Assignment Due Days   |
| Project Due Days      |
| Fees Due              |

### Predicted Alerts

| Alert            |
| ---------------- |
| Attendance Alert |
| GPA Alert        |
| CGPA Alert       |
| Assignment Alert |
| Project Alert    |
| Fee Alert        |

### Algorithm Used

K-Nearest Neighbors using **K-Nearest Neighbors**

### Files

| File                  | Description                  |
| --------------------- | ---------------------------- |
| create_dataset.py     | Synthetic dataset generation |
| student alerts.csv    | Dataset                      |
| model_for_alert.ipynb | Model training               |
| knn_model.pkl         | Trained KNN model            |
| scaler.pkl            | Feature scaler               |

---

# Model 3 – AI Quiz and GPT Learning System

This module provides a **quiz-based AI learning system** using client-server architecture.

It simulates interaction between:

• Quiz application
• AI response server
• GPT-style assistant

### Components

| File              | Purpose               |
| ----------------- | --------------------- |
| create_dataset.py | Generate quiz dataset |
| quiz.py           | Quiz logic            |
| quiz_server.py    | Quiz backend server   |
| quiz_client.py    | Quiz frontend client  |
| tgpt_server.py    | GPT simulation server |
| tgpt_client.py    | Client interaction    |

### Functionality

• Interactive quizzes
• AI response generation
• Client-server communication

---

# Model 4 – Reading Behavior Detection Model

This model detects **student reading engagement** using behavioral metrics.

### Input Features

| Feature                  |
| ------------------------ |
| Total Pages              |
| Book Complexity          |
| Readability Score        |
| Reading Engagement Index |
| Estimated Reading Time   |
| Actual Reading Time      |
| Scroll Speed             |
| Scroll Depth             |
| Backtracking Rate        |
| Page Jump Rate           |
| Exit Frequency           |

### Output

```
Flag
```

Flag indicates abnormal reading behavior such as:

• Skimming
• Lack of engagement
• Possible plagiarism

### Algorithm Used

**Random Forest**

### Files

| File                          | Description             |
| ----------------------------- | ----------------------- |
| create_dataset.py             | Dataset generator       |
| balanced_reading_behavior.csv | Training dataset        |
| model_for_doc.ipynb           | Model training notebook |
| random_forest_model.pkl       | Trained model           |

---

# Model 5 – Student Event Recommendation System

This model recommends **events and opportunities** for students based on their interests and performance.

### Input Features

| Feature           |
| ----------------- |
| Student ID        |
| CGPA              |
| Past Events       |
| Interest Domain   |
| Performance Score |

### Output

| Output               |
| -------------------- |
| Recommended Events   |
| Personalized Message |

### Files

| File                                  | Description                  |
| ------------------------------------- | ---------------------------- |
| enhanced_student_recommendations.csv  | Base dataset                 |
| generated_student_recommendations.csv | Generated recommendations    |
| final.ipynb                           | Model training               |
| recommendation_model.pkl              | Trained recommendation model |

---

# Synthetic Dataset Generation

Each model includes a script:

```
create_dataset.py
```

This script automatically generates **synthetic training datasets**, which helps simulate realistic educational data without using real student information.

---

# How to Run the Models

Install dependencies:

```bash
pip install pandas numpy scikit-learn
```

Run dataset generation:

```
python create_dataset.py
```

Train or test models using:

```
Jupyter Notebook
```

---

# Applications

These models can be used for:

• Student performance prediction
• Academic early warning systems
• Educational recommendation engines
• Smart learning analytics
• AI-assisted education platforms

---

# Hackathon Impact

During the **Wonders of AI 2.0 Hackathon**, these models were designed as part of an **AI-powered education analytics system**.

The project demonstrated:

• Predictive analytics for students
• AI-driven alerts and monitoring
• Intelligent recommendation systems
• Behavioral analysis in education

The project secured **5th place among 70+ teams**.

---

# Author

Abinesh N

GitHub
[https://github.com/Abineshabee](https://github.com/Abineshabee)

---

