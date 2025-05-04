
# Sanjeevani: Healthcare Management System

**Sanjeevani** is a smart, web-based healthcare management platform designed to simplify medical services for patients, healthcare providers, and administrators. It integrates intelligent tools like disease prediction, personalized diet planning, electronic health records (EHR), and doctor search to provide quick, reliable, and user-friendly health assistance.

---

## Features

- **Disease Prediction**  
  Upload CBC reports (PDF or JPG), and the AI-powered engine will analyze key biomarkers and predict potential health risks using automated data extraction and ML models.

- **Personalized Diet Plans**  
  Users receive custom meal plans based on age, weight, health conditions, and goals. Meals are structured with appropriate nutrients and daily recommendations.

- **Find a Specialist**  
  Patients can search doctors by location and specialization, helping them quickly connect with the right healthcare professionals.

- **Electronic Health Records (EHR)**  
  Securely store, manage, and access medical reports in a structured, encrypted format to ensure privacy and ease of use.

---

## Tech Stack

- **Frontend**: HTML, CSS  
- **Backend**: Python (Flask)  
- **Database**: MySQL  
- **AI/ML Tools**: Document AI, Cosine Similarity (for collaborative filtering)  
- **Hosting Protocol**: HTTP/HTTPS  

---

## System Highlights

- **AI Integration**: CBC report interpretation using ML-based diagnostic tools.
- **Collaborative Filtering**: Personalized diet and doctor recommendations based on similar user profiles.
- **Responsive UI**: Clean, consistent, and accessible design across all devices.
- **Security**: Encrypted storage and strict access control for EHR data.

---

## Testing Overview

Thorough testing was conducted to ensure stability and correctness:
- Functional Testing (Login, Uploads, Search, Plans)
- UI & Responsiveness Testing
- Database Validation (MySQL)
- Error Handling & Validation Messages

---

## Installation Guide

> For academic/demo purposes only.

1. Clone the repository  
   ```bash
   git clone https://github.com/your-repo/sanjeevani.git
   ```


   

2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

3. Configure the MySQL database and update credentials .

4. Run the app  
   ```bash
   flask run
   ```

---

## Sample Modules

- `Login/Register` forms
- `Upload CBC Report`
- `Find Doctor by Location/Specialization`
- `View/Manage Diet Plan`
- `Store/View Medical Reports`

---

