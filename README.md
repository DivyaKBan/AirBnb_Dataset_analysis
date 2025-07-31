# 📊 Data Analysis Project

## 📌 Overview
This project performs **data cleaning, exploratory data analysis (EDA), and visualization** on a dataset (`datasets.csv`).  
It involves handling missing values, removing duplicates, type casting, and creating meaningful visualizations to understand the dataset better.

---

## 📂 Project Structure
```
Project_1.ipynb   # Jupyter Notebook with full code
datasets.csv       # Dataset used in the analysis
README.md          # Project Documentation
```

---

## 🚀 Features
✅ Load and explore dataset  
✅ Handle missing values & duplicates  
✅ Perform type casting for relevant columns  
✅ Generate descriptive statistics  
✅ Perform **univariate & bivariate analysis**  
✅ Visualize insights using **Matplotlib & Seaborn**  

---

## 🛠️ Tech Stack
- **Python 3.x**
- **Pandas, NumPy** – Data handling & processing  
- **Matplotlib, Seaborn** – Data Visualization  
- **Jupyter Notebook**

---

## Analysis performed--
1. Price Distribution
   
   <img width="704" height="468" alt="1output" src="https://github.com/user-attachments/assets/6f043a8a-5213-4bf5-a9d3-33523c947c9a" />
3. Price depending on neighbourhood group and room type
   
   <img width="571" height="453" alt="2output" src="https://github.com/user-attachments/assets/c21fe895-a5f7-4589-af52-c813228bc055" />
5. Reviews and price relation
   
   <img width="704" height="468" alt="3output" src="https://github.com/user-attachments/assets/f5384019-1e41-489b-993b-ac6eb7fe1363" />
7. Geographical Distribution
   
   <img width="859" height="545" alt="4output" src="https://github.com/user-attachments/assets/7f4bb6d0-1c16-4502-a799-92610363f12d" />
9. Heatmap analysis of data
    
   <img width="878" height="632" alt="5output" src="https://github.com/user-attachments/assets/51fa18c3-92ff-43e4-8fad-718812ad429a" />



## 📥 Installation & Usage
### 1️⃣ Clone this repository  
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install dependencies  
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3️⃣ Run the notebook  
```bash
jupyter notebook Project_1.ipynb
```

---

## 📊 Steps Performed in the Notebook
1️⃣ **Data Loading** – Imported dataset using Pandas.  
2️⃣ **Data Cleaning** – Removed null values, duplicates, and performed type casting.  
3️⃣ **Descriptive Statistics** – Used `.describe()`, `.shape`, `.dtypes` for insights.  
4️⃣ **Exploratory Data Analysis (EDA)** –  
   - Univariate analysis using histograms & boxplots.  
   - Outlier detection (`price < 1500`).  
5️⃣ **Visualization** – Used Seaborn & Matplotlib for better understanding of data.  

---

## 📈 Sample Visualizations
- Distribution plots of numeric columns  
- Boxplots for outlier detection  
- Correlation heatmap  

---

## 📌 Results & Insights
🔹 Cleaned dataset with consistent data types  
🔹 Identified and removed duplicates & null values  
🔹 Extracted statistical insights and visual patterns  
