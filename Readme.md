# Student Placement Data Analysis & Exploratory Data Analysis (EDA)

This repository contains a Python Data Analysis notebook focused on exploring and visualizing student academic performance (CGPA, IQ) and its relationship with job placement outcomes.

---

## 📌 Project Overview

The objective of this project is to analyze a dataset of student performance parameters to understand how **CGPA** and **IQ** correlate with **Placement status**. The analysis includes data cleaning, summary statistics, numerical calculations using NumPy, and data visualizations using Matplotlib.

---

## 📊 Dataset Overview

The analysis is performed on `placement.xls` (or `placement.csv`), containing **100 records** across the following features:

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `Unnamed: 0` | `int64` | Row index/ID |
| `cgpa` | `float64` | Cumulative Grade Point Average (Scale ~3.3 to 8.5) |
| `iq` | `float64` | Intelligence Quotient score |
| `placement` | `int64` | Target variable: `1` = Placed, `0` = Not Placed |

---

## 🚀 Key Highlights & Insights

1. **Dataset Integrity**: Checked for missing values—the dataset contains **0 null values** across all columns.
2. **Balanced Target Variable**: 
   - **Placed (1)**: 50 students
   - **Not Placed (0)**: 50 students
3. **Statistical Summary**:
   - **Highest CGPA**: `8.5`
   - **Average IQ**: `123.58`
   - **Combined (CGPA + IQ) Mean**: `64.7855`
4. **Data Visualization**:
   - **Scatter Plot (`CGPA` vs `IQ`)**: Visualizes the relationship and spread between academic performance and IQ scores.
   - **Histogram (`CGPA` Distribution)**: Visualizes the distribution frequency of students' CGPAs.

---

## 🛠️ Tech Stack & Dependencies

- **Language**: Python 3.x
- **Environment**: Jupyter Notebook / Google Colab
- **Libraries**:
  - `pandas` — Data loading, inspection, and manipulation
  - `numpy` — Mathematical and array operations
  - `matplotlib` — Data visualization and plotting

---

## 💻 How to Run

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name