🩺 Diabetes Prediction Web Application
A full-stack web application for predicting diabetes based on medical parameters. Built with FastAPI and vanilla JavaScript.

✨ Features
✅ Clean and modern user interface

✅ Real-time input validation

✅ Responsive design (mobile-friendly)

✅ Fast and accurate predictions using a trained ML model

✅ Smooth animations and transitions

✅ Comprehensive error handling for a better user experience


🛠️ Prerequisites
Python 3.8 or higher

pip (Python package manager)

A modern web browser

🚀 Setup Instructions
1. Clone the repository
bash
Copy
Edit
git clone <repository-url>
cd diabetes_web
2. Create a virtual environment (optional but recommended)
bash
Copy
Edit
python -m venv venv
# On macOS/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate
3. Install required packages
bash
Copy
Edit
pip install -r requirements.txt
▶️ Running the Application
1. Start the FastAPI backend
bash
Copy
Edit
python app.py
The API will be available at: http://localhost:8000

2. Open the frontend
Option 1 – Open directly:
Open index.html in your browser.

Option 2 – Use a local server (recommended):
bash
Copy
Edit
python -m http.server 8080
Then visit: http://localhost:8080

🧪 API Documentation
Once the backend is running, access:

Swagger UI: http://localhost:8000/docs

ReDoc UI: http://localhost:8000/redoc

📋 Usage Guide
Fill in the form with the following medical parameters:

Number of Pregnancies

Glucose Level

Blood Pressure

Skin Thickness

Insulin Level

BMI

Diabetes Pedigree Function

Age

Click "Predict".

The prediction will be displayed in a result card below the form.

✅ Input Validation
Glucose, BMI, and Age must be greater than 0

All other parameters must be non-negative

Inputs are restricted to realistic medical ranges

⚠️ Error Handling
The app handles:

❌ Invalid input values

❌ Backend/server issues

❌ Network/API errors

Clear error messages are shown to the user in each case.

🤝 Contributing
Contributions are welcome!
Feel free to:

Report issues

Suggest enhancements

Submit pull requests

## Images 
![case 1](image.png)
![case 2](image-1.png)
![ui](image-2.png)
