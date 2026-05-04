# Disease Diagnosis & Drug Recommendation System

An advanced AI-powered health management platform designed by **Himanshu Jain**. This system identifies potential diseases based on user-reported symptoms and provides automated drug recommendations using Machine Learning.

## 🚀 Features
- **Symptom-Based Diagnosis**: Uses a Random Forest Classifier to predict diseases with high accuracy.
- **Drug Recommendation**: Intelligent AI mapping of diseases to recommended medications.
- **Doctor-Patient Portal**: Separate dashboards for healthcare providers and patients.
- **Appointment Management**: Patients can book consultations, and doctors can manage schedules.
- **Profile Management**: Secure registration and profile tracking for all users.

## 🛠️ Technology Stack
- **Backend**: Python, Django
- **Machine Learning**: Scikit-learn, Joblib, NumPy
- **Frontend**: HTML5, CSS3 (Bootstrap), JavaScript (jQuery)
- **Database**: MySQL

## 📦 Installation & Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/hjain-tech/Disease-Diagnosis-Model.git
   ```
2. **Install Dependencies**:
   ```bash
   pip install django numpy scikit-learn joblib mysqlclient
   ```
3. **Configure Database**: Update `healthcare/settings.py` with your MySQL credentials.
4. **Run Migrations**:
   ```bash
   python manage.py migrate
   ```
5. **Start Server**:
   ```bash
   python manage.py runserver
   ```

## 👨‍💻 Author
Developed and Maintained by **Himanshu Jain**.
