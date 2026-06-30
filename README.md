# 🌾 Rice Up

> An award-winning undergraduate thesis project that leverages Artificial Intelligence and modern web technologies to support Filipino palay farmers through rice leaf disease detection and practical farming assistance.

![Status](https://img.shields.io/badge/Status-Completed-success)
![Academic Project](https://img.shields.io/badge/Project-Undergraduate%20Thesis-blue)
![Platform](https://img.shields.io/badge/Platform-Mobile--Accessible%20Web%20Application-green)
![License](https://img.shields.io/badge/License-Academic-lightgrey)

---

## 📖 About the Project

Rice Up is a mobile-accessible web application developed as our undergraduate thesis at **De La Salle University – Dasmariñas**.

The project was designed to help **Filipino palay farmers**, particularly those in **Naic, Cavite**, by providing an accessible digital platform for identifying rice leaf diseases and offering practical farming support tools.

Unlike many existing agricultural applications that focus on a single function, Rice Up integrates multiple features into one system while keeping the interface simple and beginner-friendly for farmers with limited digital literacy.

The system combines Artificial Intelligence, cloud computing, and web technologies to provide:

- AI-powered rice leaf disease detection
- Pest detection
- Farming calendar
- Filipino virtual farming assistant
- Rice price monitoring

The application emphasizes accessibility by providing Filipino-language guidance, intuitive navigation, and mobile-friendly interfaces suitable for real-world agricultural use.

---

# 🏆 Awards and Recognition

- 🥇 **1st Place – Technology Exhibit**
  - 2nd Conference on Technology and Research for National Development and Sustainability (ConTReNDS)
  - De La Salle University – Dasmariñas
  - April 2026

- 🏅 **Best Paper Presentation Finalist**
  - International Conference on Artificial Intelligence (ICAI 2026)
  - February 2026

- 🎓 **Best Thesis (Departmental)**
  - Bachelor of Science in Computer Science
  - De La Salle University – Dasmariñas
  - June 2026

---

# ✨ Features

## 🌱 Rice Leaf Disease Detection

Uses a Convolutional Neural Network (CNN) model based on the VGG16 architecture to classify rice leaf diseases from uploaded images.

Supported disease classes include:

- Bacterial Leaf Blight
- Brown Spot
- Leaf Blast
- Leaf Scald
- Tungro
- Narrow Brown Leaf Spot
- Rice Hispa Damage
- Sheath Blight
- Healthy

---

## 🐛 Pest Detection

A separate CNN model determines whether uploaded leaf images contain signs of pest-related damage through binary classification.

- Pest Detected
- Healthy / No Pest Detected

---

## 🤖 AskJuan Virtual Assistant

A Filipino-language virtual assistant that provides farming information through predefined questions based on trusted agricultural references.

Topics include:

- Rice farming practices
- Disease information
- Pest management
- Farming recommendations
- Agricultural guidance

---

## 📅 Farming Calendar

Allows farmers to:

- Schedule farming activities
- Track important dates
- Manage planting schedules
- Organize harvesting timelines

Calendar entries are synchronized through Firebase Firestore.

---

## 💹 Rice Price Listing

Displays processed rice price information using publicly available datasets from the Philippine Department of Agriculture.

Includes:

- Current prices
- Historical data
- Simple linear regression forecasts

---

# 🖥️ Repository Scope

> **This repository contains only the frontend of the Rice Up system.**

The complete thesis project consists of multiple independent components deployed separately during development.

### Included in this repository

- HTML
- CSS
- JavaScript
- Responsive web interface
- Client-side application logic
- API integrations
- User interface for all application modules

### Not included

The following components were deployed independently and are **not part of this repository**:

- Flask Machine Learning API
- CNN models
- Google Colab deployment
- Node.js backend
- Firebase configuration
- Firestore database
- Render deployment

---

# 🏗️ System Architecture

```
                    Rice Up

        HTML • CSS • JavaScript
             (Frontend)

                   │
        ──────────────────────────

        Flask Machine Learning API
      (Google Colab + TensorFlow)

         • Disease Detection
         • Pest Detection

                   │

         Node.js Backend (Render)

        • Rice Price API
        • Regression Analysis

                   │

Firebase Authentication & Firestore

        • User Authentication
        • Farming Calendar
        • User Data
```

---

# 🛠️ Technologies Used

## Frontend

- HTML5
- CSS3
- JavaScript

## Machine Learning

- Python
- TensorFlow
- Keras
- VGG16 CNN
- Flask

## Backend

- Node.js
- Express.js
- CSV Parser
- Linear Regression

## Cloud Services

- Google Colab
- ngrok
- Render
- Firebase Authentication
- Firebase Firestore

---

# 🎯 Research Objectives

Rice Up was developed to:

- Detect rice leaf diseases using Convolutional Neural Networks.
- Assist farmers in identifying pest-related damage.
- Improve accessibility through Filipino-language guidance.
- Support farming schedules using a digital calendar.
- Provide transparent rice price information.
- Develop an integrated farming support platform tailored to Filipino farmers.

---

# 👨‍💻 Development Methodology

The project followed the **Agile Software Development Methodology**, dividing the system into iterative sprints:

- Sprint 1 – Rice Leaf Disease Detection
- Sprint 2 – Pest Detection
- Sprint 3 – AskJuan Virtual Assistant
- Sprint 4 – Farming Calendar
- Sprint 5 – Rice Price Listing

---

# 👥 Researchers

- **Rojean B. Peñano**
- **Khrystel Ann C. Guisihan**
- **Daniel D. Planada**

**Thesis Adviser**

Ms. Josephine T. Eduardo

College of Information and Computer Studies

De La Salle University – Dasmariñas

---

# 📌 Note

This repository is maintained for portfolio and documentation purposes.

The original thesis project was developed collaboratively by the researchers listed above. This repository preserves the frontend implementation while documenting the complete Rice Up system developed during our undergraduate thesis.


## 📷 Screenshots

> Screenshots of the application interface will be added soon.
