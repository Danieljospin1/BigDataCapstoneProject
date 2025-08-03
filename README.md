## Names & Id: BISUBIZO Daniel Jospin 26695

## Project Name
#  Predicting Academic Outcomes and Risk Patterns in Students

> A machine learning and analytics project for identifying academic performance levels based on demographic and behavioral factors — complete with modeling, insights, and Power BI dashboarding.

---

## Project Overview

This capstone project for **Big Data Analytics** focuses on predicting student academic outcomes and identifying risk patterns using key attributes such as gender, race/ethnicity, parental education level, lunch type, and test preparation status.

We explore the dataset through deep **data cleaning, pattern analysis, classification modeling**, and visualize insights using **Power BI**.

---

## Dataset

- **Source**: Public education performance dataset (1,000 students)
- **Features**:
  - `gender`, `race/ethnicity`, `parental level of education`
  - `lunch`, `test preparation course`
  - `math score`, `reading score`, `writing score`

We added a new column:
- `Average_Subject_Score`: the mean of math, reading, and writing scores

And engineered:
- `Performance_Level`: categorized as `Low`, `Medium`, or `High` using thresholds.

---

## 🔍 Patterns Discovered

Here are some of the **key insights** from the dataset:

| Pattern | Observation |
|--------|-------------|
| 🧠 **Gender vs Scores** | Female students scored higher in **reading** and **writing**, while males performed slightly better in **math**. |
| 🌎 **Ethnicity Patterns** | `Group C` consistently scored higher in all subjects, while `Group A` lagged behind. |
| 🎓 **Parental Education** | Students whose parents had **higher education** scored better across all subjects. |
| 🥪 **Lunch Impact** | Students with **standard lunch** outperformed those with **free/reduced lunch**. |
| 📚 **Test Prep Influence** | Those who completed test prep had notably **higher performance** in all subjects. |

---

## Model Training

- **Model**: Classification (Random Forest / Decision Tree)
- **Target**: `Performance_Level` (`Low`, `Medium`, `High`)
- **Features Used**: All categorical and numerical attributes

### 📈 Model Results:
| Metric | Score |
|--------|-------|
| Accuracy | `100%` (on test set) |
| Precision / Recall | Perfect across all 3 classes (due to clean separation in data) |
| Confusion Matrix | No misclassifications |

> 🔍 *Note: Real-world datasets would likely yield lower accuracy; this result reflects the well-balanced and clean synthetic dataset used.*

---

## 📊 Power BI Dashboard

We designed a dashboard with **three sections**:

### 1 **Demographic Performance Analysis**
- Average subject scores by gender
- Average subject scores by race/ethnicity

### 2 **Parental & Behavioral Influence**
- Performance level by parental education
- Performance level by test prep status
- Lunch type vs average score

### 3 **Overall Trends**
- Average subject score vs performance level
- Total number of students per performance group
- KPI Cards for:
  - Average Math Score
  - Average Reading Score
  - Average Writing Score
  - Total Students

---

## Screenshots
![Dashboard Overview](https://github.com/Danieljospin1/BigDataCapstoneProject/blob/22bd63b53e2aa4ee97ebdae3e9e3fb8bece11a4d/Screenshot%202025-08-03%20141033.png)
![screenshot](https://github.com/Danieljospin1/BigDataCapstoneProject/blob/22bd63b53e2aa4ee97ebdae3e9e3fb8bece11a4d/Screenshot%202025-08-03%20141834.png)
![screenshot](https://github.com/Danieljospin1/BigDataCapstoneProject/blob/22bd63b53e2aa4ee97ebdae3e9e3fb8bece11a4d/Screenshot%202025-08-03%20141908.png)
![screenshot](https://github.com/Danieljospin1/BigDataCapstoneProject/blob/22bd63b53e2aa4ee97ebdae3e9e3fb8bece11a4d/Screenshot%202025-08-03%20141939.png)
![screenshot](https://github.com/Danieljospin1/BigDataCapstoneProject/blob/22bd63b53e2aa4ee97ebdae3e9e3fb8bece11a4d/Screenshot%202025-08-03%20142013.png)
![screenshot](https://github.com/Danieljospin1/BigDataCapstoneProject/blob/22bd63b53e2aa4ee97ebdae3e9e3fb8bece11a4d/Screenshot%202025-08-03%20142109.png)


