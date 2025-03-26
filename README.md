# Customer-satisfaction-prediction
# Customer Satisfaction Prediction 🚀

## 📌 Project Overview
Customer satisfaction plays a crucial role in improving business services. This project aims to predict **customer satisfaction ratings** using machine learning techniques on customer support ticket data. The model analyzes various factors like **ticket type, resolution time, and priority level** to determine satisfaction levels.

## 📊 Dataset Overview
- **Dataset Source:** Customer Support Ticket Dataset
- **Features:**
  - Ticket Type (e.g., Billing Inquiry, Technical Issue)
  - Ticket Status (Open, Closed, Pending)
  - Resolution Time (Time taken to resolve the issue)
  - Customer Demographics (Age, Gender, Product Purchased)
  - Customer Satisfaction Rating (Target Variable, Scale 1-5)

## 🔬 Methodology
### **1️⃣ Data Preprocessing**
- Removed missing values and handled categorical data using **Label Encoding**.
- Scaled numerical features using **StandardScaler**.

### **2️⃣ Exploratory Data Analysis (EDA)**
- Analyzed customer complaint trends.
- Identified **most common ticket types** and their impact on satisfaction.
- Visualized **ticket resolution time vs. satisfaction ratings**.

### **3️⃣ Model Training & Evaluation**
- **Algorithm Used:** Random Forest Classifier
- **Evaluation Metrics:**
  - **Accuracy Score**
  - **Classification Report (Precision, Recall, F1-score)**
  - **Confusion Matrix for Performance Analysis**
- **Feature Importance Analysis:** Identified key factors affecting customer satisfaction.

## 📈 Results & Insights
- **High-priority tickets** tend to have **lower satisfaction ratings**.
- **Technical issues and billing inquiries** are major drivers of dissatisfaction.
- Faster resolution times correlate with **higher customer satisfaction**.

## 🚀 Future Scope
- Implementing **NLP-based ticket classification** to improve automation.
- Experimenting with **Deep Learning models** for better prediction accuracy.
- Deploying the model as a **web application** using Flask or Streamlit.


