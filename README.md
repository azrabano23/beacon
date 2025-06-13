# 🔥 BEACON – Real-Time Wildfire Detection & Emergency Response System  
**Group 2 – HackRU Spring 2025**  
Team Members:  
- Nithik Pandya  
- Krisha Jhala  
- Preet Patel  
- Azra Bano  

---

## 🚨 Overview

**Beacon** is an advanced wildfire detection and evacuation planning platform that combines **NASA’s FIRMS fire data**, **AI-driven analytics**, and **real-time routing** to help communities, first responders, and public health officials make faster, smarter decisions during wildfire emergencies.

---

## ❗ Problem Statement

Wildfires are becoming more **frequent**, **unpredictable**, and **devastating** due to climate change. Traditional fire response systems are often static, slow, and ineffective at dealing with modern mega wildfires.

> 🔥 *In early 2025, wildfires in California killed 29 people, destroyed over 16,000 structures, and exposed millions to toxic air.*  
> *(Source: LA County Environmental Health Watch, 2025)*

A recent IEEE study found that current wildfire systems:
- Cannot predict erratic fire behavior like fire tornadoes or pyrocumulonimbus clouds.
- Rely on outdated, non-interactive visualization tools.
- Fail to provide real-time risk assessments or dynamic evacuation planning.
- Lack support for public health monitoring during recovery phases.

---

## ✅ Our Solution: BEACON

Beacon closes these gaps by providing a **real-time, AI-powered wildfire safety platform**, combining emergency alerts, evacuation guidance, and predictive analytics into one unified system.

### 🔍 Key Features

- **📡 Live NASA FIRMS Fire Data**  
  Real-time detection of active wildfire locations across the globe.

- **🚗 Dynamic AI-Powered Evacuation Routes**  
  Leverages **Google Maps** and **Waze** APIs to instantly reroute users based on real-time road conditions, fire proximity, and closures.

- **🌫️ Air Quality Monitoring**  
  Integrates **AirNow API** to provide live AQI updates and **smoke drift predictions**, supporting safer evacuation and health decisions.

- **🧠 Fire Spread Prediction Engine**  
  Uses **NOAA weather data** (wind, humidity, temperature) and machine learning to model and visualize likely fire movement.

- **📲 Emergency Alerts for Offline Zones**  
  Sends alerts via **Twilio SMS** and **LoRaWAN** for areas with poor internet access, aiding both citizens and first responders.

---

## 🌎 Why This Matters

- **🔐 Emergency Preparedness**: Traditional tools can’t adapt fast enough to new threats — Beacon delivers real-time adaptability and awareness.  
- **🚧 Smart Evacuation Routes**: Go beyond static fire maps with dynamic, AI-generated paths to safety.  
- **🩺 Public Health Protection**: Visualizes smoke spread and air quality to help communities understand when to evacuate or shelter.  
- **🌍 Climate Resilience Tool**: Helps governments and responders better plan for an era of more extreme wildfires.

---

## 🛠️ Technologies Used

| Category     | Tools Used                                 |
|--------------|---------------------------------------------|
| Frontend     | React (Map UI, Dashboard)                  |
| Backend      | Node.js, Python                            |
| APIs         | NASA FIRMS, Google Maps, Waze, AirNow, NOAA|
| Messaging    | Twilio SMS, LoRaWAN                        |
| Hosting/API  | FastAPI (with `uvicorn` server)            |

---

## 🧪 Getting Started

### 🔧 Prerequisites
- Install [Node.js](https://nodejs.org/)
- Install [Python 3.x](https://www.python.org/)

### 📦 Install Frontend Dependencies
```bash
cd frontend
npm install
```

### 📦 Install Backend Dependencies
```bash
cd backend
npm install
```

### 🔐 Environment Configuration
Create a `.env` file in the `/backend` directory and include the following:
```env
NASA_API_KEY=your_key_here
GOOGLE_MAPS_API_KEY=your_key_here
AIRNOW_API_KEY=your_key_here
TWILIO_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token
```

### ▶️ Start Backend Server
```bash
cd backend
uvicorn main:app --reload
```

### ▶️ Start Frontend App
```bash
cd frontend
npm start
```

---

## 📈 Future Plans

- Add wildfire simulation tools for training exercises
- Public-facing mobile app for fast alerts and routing
- Integration with drone imaging for real-time fire boundaries
- Expand multilingual support and accessibility features

---

## 📄 License
This project was developed at HackRU Spring 2025 and is open for educational and non-commercial use.

---

## 🙌 Acknowledgments

Thanks to:
- **NASA FIRMS** for real-time fire data  
- **NOAA** and **AirNow** for public health insights  
- **Google Maps API** for routing intelligence  
- **HackRU** for the opportunity to build solutions that matter
