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

## 🏡 **Project 2: k-Nearest Neighbors (k-NN) for Boston Housing Prices**  

**📄 File:** `Boston Housing Prices Prediction.pdf`  
**📌 Objective:**  
To predict **housing prices** using a **k-NN regression model** and determine the **optimal value of k**.

### 🛠 **Data Preprocessing**  
- Partitioned the dataset into **training (80%)** and **testing (20%)** using `createDataPartition()`.  
- Standardized the dataset using `preProcess()` (`center` and `scale` methods).  

### 🏗 **Model Implementation**  
- Implemented **k-NN regression** using the `train()` function from the `caret` package.  
- Used **10-fold cross-validation** to evaluate performance across different values of k (**1 to 18**).  

### 📊 **Model Evaluation**  
- Evaluated models using **RMSE, R-squared, and MAE**.  
- Identified **k = 3** as the optimal value with the lowest **RMSE (0.482)**.  
- Generated a plot to **visualize RMSE values** across different k values.  

### 📌 **Final Findings**  
- The **k-NN model with k = 3** provided the best trade-off between **bias and variance**. 
---

## 📌 **Technologies & Tools Used**  
🔹 **R Programming**    
🔹 Machine Learning & Statistical Modeling  
🔹 k-nearest neighbors (k-NN) Algorithm
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
