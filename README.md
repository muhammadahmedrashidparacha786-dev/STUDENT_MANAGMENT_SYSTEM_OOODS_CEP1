Student Management System

This project was developed as part of our OODS CEP (Object-Oriented Design & Software Construction) course.
It is a fully functional Student Management System enhanced with modern DevOps and MLOps practices.

👨‍💻 Project By:

MUHAMMAD AHMED RASHID PARACHA (24K-6040)

ASAD AYUB (24K-6067)

ALI MEHDI (24K-6066)


1. Complete Development of the Student Management System

Designed and built a full-featured Student Management System using Django.

Implemented modules for student records, teacher records, attendance, courses, results, and authentication.

Refactored and improved older components to follow modern OOP and Django best practices.

2. DevOps Integration

To modernize the development workflow, we integrated DevOps practices:

Created a Dockerfile to containerize the entire application for easier deployment and environment consistency.

Set up a GitHub Actions CI pipeline that:

Automatically runs tests on each push.

Ensures code quality and reliability.

Improved developer workflow with automated checks and reproducible builds.

3. MLOps Integration

We added an intelligent ML component to enhance the system:

Developed a Grade Predictor Machine Learning model that predicts student performance.

Added a custom Django management command (retrain_model) that:

Automatically retrains the ML model on newly added database entries.

Keeps the predictions accurate and continuously updated.

Implemented a lightweight MLOps loop inside the project to maintain the ML lifecycle.