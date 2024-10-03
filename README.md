# Diabetes Prediction Web Application

## Project Overview
This project is a web-based application that allows healthcare providers or individuals to predict the likelihood of diabetes in a patient based on various health and lifestyle factors. The model is powered by a machine learning backend that analyzes inputs and predicts the probability of diabetes. This web application can help in early diagnosis and prompt medical intervention.

The project was developed as part of **DAS medhub**, an AI-driven healthcare platform designed to improve medical outcomes and accessibility in Africa and beyond.

## Features
- User-friendly web interface to input patient information.
- Takes into account factors like age, gender, BMI, family history, blood pressure, and lifestyle habits (diet, physical activity, smoking, etc.).
- Predicts diabetes likelihood using a machine learning model.
- Helps healthcare practitioners in making data-driven decisions.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Flask (or any other backend framework that interacts with the machine learning model)
- **Machine Learning:** Python (TensorFlow, Scikit-learn, Pandas, NumPy)
- **Deployment:** AWS/Azure/Heroku (based on your deployment choice)

## Getting Started

### Prerequisites
To run the project locally, you'll need:
- Python 3.8+
- A virtual environment (recommended)
- Required Python packages (see below)


5. Open your browser and visit `http://localhost:5000` to see the web interface.

### Files and Folders

- `app.py`: The main Flask backend file for the application.
- `templates/index.html`: The frontend HTML template for the user interface.
- `static/styles.css`: CSS file for styling the web application.
- `model/`: Contains the trained machine learning model and associated scripts.
- `README.md`: Project overview and instructions (this file).
- `requirements.txt`: Lists all Python packages required to run the app.

### Model
The machine learning model used in this application is a classification model that was trained on a dataset with features such as:
- **Age**
- **BMI**
- **Blood Pressure**
- **Fasting Blood Sugar**
- **HbA1c**
- **Cholesterol levels** (LDL, HDL, Total)
- **Lifestyle factors** (smoking, physical activity, diet)
- **Family history** of diabetes, etc.

The model is built using **TensorFlow** and was fine-tuned to optimize prediction accuracy for diabetes classification.

## Usage
1. Fill in the patient's information in the form.
2. Click on the 'Predict' button to obtain the diabetes prediction.
3. The result will indicate the likelihood of the patient being diabetic, based on the provided inputs.

## Future Improvements
- Add real-time data visualization for analysis.
- Include more detailed result explanations for medical professionals.
- Add integration with Electronic Health Records (EHR) systems.


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For questions or collaboration, feel free to contact **Divine Sebukpor**, founder of DAS medhub. You can also open an issue or contribute to the repository directly.

---

