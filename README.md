# **Detection of Phishing Attacks Using Random Forest Algorithm**

## 📌 Project Overview  
Phishing attacks are one of the most common cybersecurity threats, targeting users' sensitive information through fraudulent websites. This project utilizes **Machine Learning (ML)** techniques, specifically the **Random Forest Algorithm**, to classify websites into three categories: **Benign, Spam, and Malicious**.

Our system analyzes **URL lexical features** and classifies them without requiring access to the website’s core content, reducing runtime delays and ensuring user safety.

---

## 🚀 Key Features  
✅ **Machine Learning-Based Detection** – Uses **Random Forest Algorithm** and **Support Vector Machine (SVM)** for high accuracy.  
✅ **Feature Extraction** – Identifies suspicious patterns in **URLs**, including **IP addresses, URL length, special characters, and prefixes/suffixes**.  
✅ **High Efficiency** – Processes thousands of URLs efficiently to detect phishing sites.  
✅ **Scikit-Learn Implementation** – Uses Python's `scikit-learn` library for model training and evaluation.  
✅ **Anaconda Navigator Integration** – Simplifies package and environment management.  

---

---

## 🛠️ Tech Stack  
- **Programming Language**: Python 🐍  
- **Libraries Used**:  
  - `pandas` – Data handling  
  - `numpy` – Numerical computations  
  - `scikit-learn` – ML model implementation  
  - `matplotlib` – Data visualization  

- **Development Tools**:  
  - Jupyter Notebook 📓  
  - Anaconda Navigator 🏗️  

---

## 📊 Methodology  

### **1️⃣ Data Preprocessing**  
- Collected and labeled dataset of URLs  
- Removed duplicate and irrelevant entries  
- Applied **feature extraction** for classification  

### **2️⃣ Feature Extraction**  
- Checked for **IP addresses** in the URL  
- Measured **URL length** to identify unusually long or short URLs  
- Detected **special characters** used to mask phishing sites  
- Identified **prefixes & suffixes** commonly used in phishing domains  

### **3️⃣ Model Training**  
Implemented **Random Forest Algorithm** and **Support Vector Machine (SVM)**:  
- **Random Forest**: Uses multiple decision trees to improve classification accuracy  
- **SVM**: Finds the optimal hyperplane to separate phishing and benign URLs  

### **4️⃣ Evaluation & Results**  
- Trained on **3,000+ URLs**  
- Achieved **98.38% accuracy** in detecting phishing sites  

---

