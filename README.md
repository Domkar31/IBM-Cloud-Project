# **Predictive Maintenance for Industrial Machines**  
_A Capstone Project under IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies_

---

## 🌟 **Overview**
This repository contains the **capstone project** developed during the **IBM SkillsBuild 4-Week Internship**, a program jointly conducted by **IBM SkillsBuild**, **Edunet Foundation**, and **AICTE**.  

The internship focused on **AI, Machine Learning, and Cloud Computing** through hands-on experiments on **IBM Cloud**.  
This project addresses a critical industrial challenge: **predicting machine failures before they occur** to minimize **downtime** and **maintenance costs**.

---

## 📌 **Project Title**
**"Intelligent Predictive Maintenance Model for Industrial Machines"**

---

## ❓ **Problem Statement**
Unexpected machine failures result in significant **production losses** and **operational expenses**. Traditional maintenance strategies (reactive or scheduled) are not efficient, as they cannot predict when and why a failure will happen.  

The objective of this project is to:  
✔ **Predict failures before they occur**  
✔ **Classify the type of failure** (e.g., Tool Wear, Heat Dissipation, Power Failure)  
✔ **Enable proactive maintenance** to improve **efficiency** and **reduce costs**  

---

## 💡 **Proposed Solution**
We designed a **Machine Learning-based predictive maintenance system** that:  
- Processes **sensor data** from machines (temperature, vibration, load, etc.)  
- Identifies patterns that signal an upcoming failure  
- Predicts the **failure category in real time**  
- Deploys the model as a **REST API** on **IBM Cloud**, accessible for integration with **industrial monitoring systems**  

---

## ⚙ **Technology Stack**
| Component           | Details                                |
|---------------------|----------------------------------------|
| **Cloud Platform**  | IBM Cloud                            |
| **ML Service**      | IBM watsonx.ai & AutoAI             |
| **Programming**     | Python                               |
| **Libraries**       | pandas, scikit-learn, XGBoost, ibm-watsonx-ai |
| **Deployment**      | IBM Cloud Deployment Space           |

---

## 🔍 **Workflow**
### **Step 1: Data Handling**
- Collected **historical sensor data** for machine operations  
- Performed **data cleaning** and **feature engineering**  

### **Step 2: Automated Model Building**
- Configured **AutoAI Experiment** in watsonx.ai  
- Automated pipeline included:  
  ✅ Data Preprocessing  
  ✅ Feature Selection  
  ✅ Model Training & Optimization  

### **Step 3: Model Selection**
- **XGBoost Classifier** emerged as the best-performing algorithm  
- Evaluated on **accuracy, precision, and recall**  

### **Step 4: Deployment**
- Exported model to **IBM Cloud Deployment Space**  
- Deployed as an **Online REST API** for real-time prediction  

### **Step 5: Testing**
- Tested API with **sample sensor readings** for predictive accuracy  

---

## 📊 **Key Outcomes**
- ✅ **Accurate failure predictions**  
- ✅ **Reduced downtime** through proactive maintenance  
- ✅ **Scalable solution** for large industrial systems  
- ✅ Successfully deployed **real-time inference API** on IBM Cloud  

---

## 📂 **Repository Structure**
📁 Predictive-Maintenance-IBM
│── 📄 Predictive_Maintenance_Model.ipynb # AutoAI-generated notebook
│── 📄 OmkarDesaiProjectTemplate.pdf # Final presentation
│── 📄 README.md # Documentation


---

## 🖼 **Screenshots**
The deployed model demonstrated high accuracy in classifying infrastructure projects, proving the effectiveness of using automated AI tools for rapid development and deployment. The project successfully met all requirements for the final evaluation and submission.
<img width="1831" height="800" alt="image" src="https://github.com/user-attachments/assets/668027b6-4cbc-43e2-b522-bc8a331ad0ad" />
<img width="1850" height="889" alt="image" src="https://github.com/user-attachments/assets/e319a9da-da51-44b0-b46f-c469f47fb364" />
<img width="1784" height="766" alt="image" src="https://github.com/user-attachments/assets/2858fb7d-3811-4623-9365-3de6f037156c" />
**Accuracy show in following model :**
<img width="1214" height="555" alt="image" src="https://github.com/user-attachments/assets/b6d43367-6ff7-4340-a2dd-e189c0867a34" />

<img width="1693" height="798" alt="image" src="https://github.com/user-attachments/assets/d95f6253-000b-438e-9860-47ddf39ae6b2" />
<img width="1776" height="555" alt="image" src="https://github.com/user-attachments/assets/7be91e5f-7ae2-4e47-ae3e-d175efdf47fe" />







---

## 🎓 **Internship Details**
- **Intern Name:** Omkar Uday Desai  
- **Institute:** Sant Gajanan Maharaj College of Engineering, Mahagaon  
- **Duration:** 15th July 2025 – 7th August 2025  
- **Organizers:** IBM SkillsBuild | Edunet Foundation | AICTE  

---

## ✅ **Next Steps / Future Scope**
- Integrate with **IoT sensors** for live data streaming  
- Use **deep learning models** for enhanced accuracy  
- Implement **dashboard for real-time monitoring**  

---

