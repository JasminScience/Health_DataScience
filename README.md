# Health_DataScience
Machine Learning model to predict heart disease presence using clinical data. Built with Python and Scikit-Learn. (Accuracy: 87%)
# Heart Disease Prediction using Machine Learning 🫀

This project aims to predict the presence of heart disease in patients based on clinical medical data. By leveraging classification algorithms, the model provides an early screening tool to help identify high-risk individuals.

The model achieved high performance with balanced metrics, ensuring that positive cases are captured effectively:

- **Accuracy:** 87%
- **Recall (Class 1):** 88% — *Crucial for medical diagnosis to minimize false negatives.*
- **F1-Score:** 0.89
- **Precision:** 90% (for positive cases)

Features & Data Preprocessing
The dataset includes several clinical features that were preprocessed using techniques like **One-Hot Encoding** and **Feature Scaling**.

 Key Variables:
- **Demographics:** Age, Sex (Encoded).
- **Vital Signs:** Resting Blood Pressure (`RestingBP`), Cholesterol, Fasting Blood Sugar (`FastingBS`), and Max Heart Rate (`MaxHR`).
- **Clinical Tests:** Exercise-induced Angina, Oldpeak (ST depression), and Chest Pain Type (ATA, NAP, TA).
- **Target:** `HeartDisease` (1 = Presence, 0 = Absence).

 Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Algorithm:** [Insert your algorithm here, e.g., Random Forest or Logistic Regression]

Results
The classification report shows that the model is very robust:
- It successfully identifies **88% of patients with heart disease**.
- It maintains a high precision of **90%**, meaning it has a low rate of false alarms.



 This project is for educational purposes and should not be used as a replacement for professional medical diagnosis.*
