# Face Factor Authentication  

## Overview  
**Face Factor Authentication** is a mobile application that enhances cybersecurity by using facial recognition and emotion-based authentication. The app ensures secure access to sensitive transactions by requiring a user's unique facial expression for authentication.  

Developed under an **NSA CRADA program**, this project aims to tackle modern cybersecurity concerns by introducing an additional layer of biometric authentication, making it significantly harder for attackers to gain unauthorized access.  

## Features  
- **Facial Recognition**: Identifies users based on their facial features.  
- **Emotion-Based Authentication**: Users authenticate with a specific facial expression.  
- **Multi-Layered Security**: Combines traditional login methods with biometric authentication.  
- **User-Friendly Interface**: Clean and intuitive UI for easy navigation.  
- **Account Management**: Allows users to register, manage, and secure their accounts.  

---

## Technical Architecture  

### Technology Stack  
- **Backend**: Gradle  
- **Database**: MongoDB (stores user facial image data securely)  
- **Mobile App**: Kotlin (Android)  
- **Machine Learning Models**: Python (Google Colab)  
- **Datasets**: Kaggle (for training facial and emotion recognition models)  

### System Workflow  
#### 1. **User Registration**  
- New users create an account.  
- Facial images and expressions are registered in the database.  
- Users link accounts for authentication.  

#### 2. **User Authentication**  
- The app scans the user’s face using the front-facing camera.  
- Compares the scan against stored facial data in MongoDB.  
- If a match is found, the user confirms their identity.  

#### 3. **Data Storage Strategy**  
- **Facial images & expressions**: Stored in a secure database for quick retrieval.  
- **User data & login history**: Managed separately in a flat-file system.  
- **Dynamic Model Updates**: Allows users to update their facial authentication settings.  

### Deployment  
- **Platform**: Android mobile devices  
- **Architecture**: Model-View-Controller (MVC) to separate UI from backend logic  
- **Authentication Flow**: Facial & emotion recognition models run separately from the core app logic.  

---

## Machine Learning Models  

### **Expression Recognition Model**  
- **Task**: Multi-Class Classification  
- **Model**: CNN (Convolutional Neural Network)  
- **Loss Function**: Cross-Entropy Loss  
- **Evaluation Metric**: AUC-ROC (Area Under the Curve - Receiver Operating Characteristic)  

### **Facial Recognition Model**  
- **Task**: One-Shot Recognition  
- **Model**: Siamese Neural Network  
- **Loss Function**: Triplet Loss  
- **Evaluation Metric**: Cosine Similarity  

---

## Achievements  
✅ Developed a working **facial and emotion recognition model**  
✅ Designed a **user-friendly mobile application**  
✅ Implemented **secure authentication for transactions**  
✅ Integrated a **multi-layered data storage strategy**  
✅ Gained valuable experience in **software development cycles**  

---

## Collaboration with NSA  
This project was developed with support from the **NSA CRADA program**, providing valuable insights into:  
- Secure software development practices  
- Agile development & sprint cycles  
- Expanding the project’s scope with expert guidance  
