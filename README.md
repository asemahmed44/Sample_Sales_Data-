
# 📈 Sales Data Analysis using Python & Machine Learning

This project performs comprehensive analysis on **retail sales data**, including data cleaning, preprocessing, visualization, and building a predictive machine learning model.  
The workflow helps uncover trends in sales, understand product performance, and forecast revenue using historical data.

---

## 📌 Project Overview

The goal of this project is to analyze structured sales data to extract valuable insights and build a prediction model.  
The analysis includes:

- Sales trends over time  
- Product-level performance  
- Customer purchasing behavior  
- Revenue patterns  
- Building a regression model to predict sales  

The project is fully implemented in Python.

---

## 📂 Dataset Used

Dataset: **Sample Sales Data**

Contains information such as:

- Order ID  
- Customer ID  
- Product  
- Quantity  
- Unit Price  
- Total Price  
- Order Date  

This dataset represents transactional sales records used for analysis and ML prediction.

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook / Script  

---

## 🧹 Data Preprocessing

✔ Loaded dataset using Pandas  
✔ Checked & removed missing/duplicate rows  
✔ Converted date columns to datetime format  
✔ Engineered new features (Month, Year, Revenue)  
✔ Converted numeric columns to appropriate types  
✔ Prepared dataset for machine learning  

---

## 🔍 Analysis Steps

### **1️⃣ Load the Dataset**
Import data and explore basic statistics.

### **2️⃣ Clean & Process the Data**
- Fix data types  
- Remove invalid rows  
- Handle missing values  
- Add time-based features  

### **3️⃣ Exploratory Data Analysis**
Includes:

- Monthly sales trends  
- Most sold products  
- Highest revenue categories  
- Customer behavior insights  

### **4️⃣ Build ML Model**
A regression model is trained to predict total sales value.

---

## 🤖 Machine Learning Model

A **Linear Regression** model was implemented to predict:

```

Total Sales = Quantity × Unit Price + Additional Features

````

Model steps:

- Split dataset into train/test sets  
- Fit the regression model  
- Evaluate predictions using **Mean Squared Error (MSE)** and **R² Score**  

---

## 📊 Key Insights

- Clear seasonal sales patterns appear across months  
- Some products dominate total revenue  
- Customer purchasing behavior varies widely  
- Regression model gives a strong baseline for predicting future sales  

---

## 🚀 How to Run the Project

### **Install Dependencies**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
````

### **Run the Script**

```bash
python sample_sales_data.py
```

The script will:

* Load & clean the dataset
* Perform sales analysis
* Plot key graphs
* Train & evaluate the ML model

---

## 📁 Project Structure

```
sales-data-analysis/
│── sample_sales_data.py
│── sales_data.csv (if included)
│── README.md
```

---

## 📬 Contact

Created by **Asem Ahmed**
Feel free to reach out for improvements, ideas, or collaboration!

