🏦 Loan Prediction Model Deployment on AWS EC2

This project demonstrates a **Loan Approval Prediction Machine Learning Model**, deployed on an **AWS EC2 instance** using **Flask**. The model predicts whether a loan should be approved based on user inputs like income, gender, marital status, credit history, etc. A clean and responsive web interface built with HTML and CSS allows users to interact with the model.

---

## ✨ Features

- Real-time loan approval prediction
- Clean UI using HTML/CSS
- Flask backend to serve predictions
- Deployed on AWS EC2
- Uses pre-trained ML model (`loan_model.pkl`)

---

## 🛠️ Tech Stack

- **Languages**: Python, HTML, CSS
- **Libraries**: Flask, scikit-learn, pandas
- **Deployment**: AWS EC2

---

## ☁️ Deployment on AWS EC2

The model is deployed on an AWS EC2 instance. Below are the key steps followed for deployment:

1. Launched an Ubuntu EC2 instance on AWS
2. SSH into the instance
3. Installed Python, pip, Git, Flask, and other required packages
4. Cloned this GitHub repository to the server
5. Started the Flask app (`python app.py`)
6. Opened port 5000 in the EC2 security group to allow web access

---

## 🧠 Model Overview

- **Model**: (Mention your model type – e.g., Logistic Regression, Random Forest)
- **Input Features**:
  - Gender
  - Marital Status
  - Dependents
  - Education
  - Employment Status
  - Applicant Income
  - Loan Amount
  - Credit History
- **Output**: Loan Approved or Not Approved

The model was trained using publicly available loan datasets and serialized using `pickle`.

---

## 📂 Check Screenshot folder to check input page, EC2 instance, security group and passkey, model also attacted. 

