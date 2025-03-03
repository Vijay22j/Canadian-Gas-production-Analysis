# 📊 Predictive Analytics Projects  
This repository contains **Predictive Analytics** projects completed as part of my **Master’s program coursework**. These projects involve **data preprocessing, statistical analysis, machine learning model implementation, and evaluation** using **R**.

---

## 🔍 **Project 1: Canadian Gas Production Analysis**  

**📄 File:** `Canadian gas Production Analysis.pdf`  
**📌 Objective:**  
To analyze **monthly Canadian gas production** from **March 1990 to February 2005** and uncover its **seasonal patterns and trends**.

### 🛠 **Data Preprocessing**  
- Loaded the **canadian_gas** dataset from the `fpp3` package.  
- Filtered observations from **March 1990 to February 2005**.  
- Selected relevant columns (**Month** and **Volume**).  

### 📊 **Exploratory Data Analysis (EDA)**  
- Used `autoplot()` to visualize the **time series trends**.  
- Generated **seasonal subseries** and **seasonal decomposition plots** using `gg_subseries()` and `gg_season()`.  
- Identified **consistent seasonal fluctuations**, with noticeable dips in **February, June, and September**.  

### 🔎 **Time Series Decomposition**  
- Applied **STL decomposition** to break down the time series into **trend, seasonal, and remainder** components.  
- Compared **X-11** and **SEATS** decompositions.  
- Found that **STL decomposition** provided **smoother trends** and **lower deviation levels**.  

---

## 🤖 **Project 2: Support Vector Machines for Purchase Prediction**  

**📄 File:** `Purchase Prediction.pdf`  
**📌 Objective:**  
To classify **purchase behavior (FN vs. MM)** using **SVM models** and optimize the **hyperparameters** for better accuracy.

### 🛠 **Data Preprocessing**  
- Loaded the **juice2022.csv** dataset.  
- Split the data into **training (90%)** and **test (10%)** sets using `createDataPartition()`.  

### 🔬 **Model Implementation**  
- Fit an **initial SVM model** using a **linear kernel** (`svm()` function with cost = 0.01).  
- Evaluated model performance using **accuracy, training error, and test error rates**.  

### ⚙️ **Hyperparameter Tuning**  
- Used the `tune()` function to find the **optimal cost value** in the range **0.01 to 10**.  
- Found the **best cost parameter** that minimized **test error**.  

### 🔄 **Comparison of SVM Kernels**  
- Tested models with **linear, radial, and polynomial kernels**.  
- **Radial kernel performed best** with the lowest **test error rate (0.434)** after tuning.  
- **Final Recommendation:** Use **radial kernel SVM with cost = 0.5**.  

---

## 📌 **Technologies & Tools Used**  
🔹 **R Programming**    
🔹 Machine Learning & Statistical Modeling  

---

## 📌 **Packages**  

**These projects were developed using R with the following packages:**  
🔹 ggplot2    
🔹 caret  
🔹 fpp3   
🔹 rmarkdown  
🔹 e1071  
🔹 seasonal  
🔹 corrplot  
🔹 dplyr


---

## 📜 **License**  
This repository is for **academic purposes**. If you wish to use any part of this work, please provide appropriate credit 

---

## 🤝 **Authors**  
Vijay Ramaraju Jampana, Prasanth Gutha, Manasa, Fahmieh Asgari  

---

## 📩 **Contact**  
For any inquiries, reach out via **GitHub Issues** or email me directly.  
