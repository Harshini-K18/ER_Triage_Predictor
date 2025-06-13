# Emergency Room Triage Predictor

A web application that predicts the urgency level of patients in an Emergency Room (ER) setting using vital signs and symptoms, and provides an estimated wait time and recommended action.

## Features

- **Patient Data Entry:** Enter patient name, age, heart rate, temperature, oxygen saturation, pain level, AVPU, and select symptoms.
- **Urgency Prediction:** Uses a machine learning model to predict the triage level (Critical, Not Critical, Normal).
- **Estimated Wait Time:** Displays estimated wait time based on the prediction and patient vitals.
- **Recommended Action:** Suggests whether immediate medical attention is required or a routine check-up is sufficient.
- **Nearby Hospitals:** For critical cases, shows a link to nearby hospitals using Google Maps and the user's location.
- **Animated UI:** Modern, animated dashboard with medical-themed icons and a custom beating heart-stethoscope SVG.
- **Responsive Design:** Works well on desktop and mobile browsers.

## Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS (Bootstrap 4, custom styles), JavaScript
- **Icons:** Bootstrap Icons
- **Font:** Lora (Google Fonts)

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Harshini-K18/ER_Triage_Predictor.git
   cd ER_Triage_Predictor
   ```

2. **Create and activate a virtual environment:**
   ```sh
   python -m venv venv
   venv\Scripts\activate   # On Windows
   # Or
   source venv/bin/activate  # On Mac/Linux
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the app:**
   ```sh
   cd website
   python model_app.py
   ```

5. **Open your browser and go to:**
   ```
   http://127.0.0.1:5000/
   ```

## Project Structure

```
ER_Triage_Predictor/
├── website/
│   ├── static/
│   │   ├── css/
│   │   │   └── template.css
│   │   └── favicon.ico
│   ├── templates/
│   │   ├── index.html
│   │   └── home.html
│   └── model_app.py
├── requirements.txt
└── README.md
```

![Image](https://github.com/user-attachments/assets/a70bdb3d-1e52-4519-9db4-827ee9e6de1b)
![Image](https://github.com/user-attachments/assets/ea2f4b48-23b4-4f00-bde4-aee1a20a2501)
![Image](https://github.com/user-attachments/assets/d5f199a3-fa64-4a4a-ad73-f32fa844d889)
![Image](https://github.com/user-attachments/assets/154bb30f-0071-4815-858a-e0b82729ec93)
![Image](https://github.com/user-attachments/assets/4eec18e6-f1fb-49cc-b6b0-0c54bbbd62e4)
![Image](https://github.com/user-attachments/assets/99e1cf50-dd66-4365-9482-e2c093d64340)
