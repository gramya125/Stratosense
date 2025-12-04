🌫️ STRATOSENSE-APP

⚠️ Note: This system is under active development. It is not intended for medical or regulatory-grade environmental decision-making.

A full-stack web application for real-time air quality monitoring, AQI forecasting, and personalized health alerts. STRATOSENSE-APP integrates a Decision Tree ML model with FastAPI and a React-based frontend to help users track air quality trends, understand pollutant behavior, and receive automated health advisories based on risk levels.

🔍 Key Features

Real-Time AQI Monitoring – Live air quality index and pollutant data visualization

AI-Based AQI Forecasting – Decision Tree ML model predicts short-term air quality

Health Alert Engine – Automated warnings when pollution levels reach hazardous zones

Geographic Heatmaps – Region-wise AQI visualization

Interactive Dashboard – Clean and responsive UI for smooth data exploration

Full-Stack Integration – FastAPI backend + React/TypeScript frontend

📌 Architecture

Environmental Data
    ↓
FastAPI Backend → Data Processing + ML Forecast
    ↓
Decision Tree Model → AQI Prediction
    ↓
React Dashboard → Charts, Heatmaps, Alerts

🗂️ Project Structure
STRATOSENSE-APP/
├── public/                 # Static frontend assets
├── src/                    # React components & UI logic
│   ├── components/
│   ├── pages/
│   └── utils/
├── server/                 # FastAPI backend
│   ├── main.py
│   ├── routes/
│   └── ml_engine/
├── models/                 # ML model scripts & trained models
│   └── decision_tree.pkl
├── package.json            # Frontend dependencies
├── requirements.txt        # Backend dependencies
└── README.md

⚙️ Quick Start
🔧 Prerequisites

Node.js + npm

Python 3.8+

pip package manager

📥 Installation
1️⃣ Clone the Repository
git clone https://github.com/gramya125/STRATOSENSE-APP.git
cd STRATOSENSE-APP

2️⃣ Frontend Setup
npm install
npm run dev

3️⃣ Backend Setup
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn server.main:app --reload

🚀 Usage

Visit the live dashboard:

🔗 https://strato-sable.vercel.app/

STRATOSENSE-APP allows users to:

View real-time AQI levels

Explore pollutant trends

Understand historic AQI patterns

Receive AI-generated AQI forecasts

Get automated health notifications when air quality worsens

🛠 Requirements
fastapi
uvicorn
scikit-learn
pandas
numpy
python-multipart
requests

# Frontend
react
typescript
vite
chart.js
tailwindcss

📄 License

This project is licensed under the MIT License.
See the LICENSE
 file for more information.

📬 Contact

Author: Gunthala Ramya
Email: gunthala_ramya@gmail.com

GitHub: https://github.com/gramya125

⚠️ Disclaimer

STRATOSENSE-APP is a research and educational project.
It is not intended for certified environmental monitoring, health diagnostics, or emergency decision-making. Always refer to official pollution control boards and authorized meteorological departments for validated air-quality data.
