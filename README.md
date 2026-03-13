# Shadowbroker GR

**Shadowbroker GR** is a Greek localization and adaptation of the original [Shadowbroker](https://github.com/BigBodyCobain/Shadowbroker) application.

## Origin
The original application is a real-time OSINT dashboard that aggregates multiple live intelligence sources (flights, ships, earthquakes, conflicts, weather radar, etc.) onto a single 3D globe. This repository contains the complete translation of its frontend user interface into contemporary Greek, created by `z1000biker` (sv1eex@hotmail.com).

## Features
- **Full Greek UI**: All panels, popups, and legends are translated into Greek.
- **Real-time Map Layers**: Includes live commercial/military/private flights, AIS maritime tracking, GDELT conflict alerts, and more.
- **3D Visualization**: Powered by Cesium with high-resolution satellite imagery support.


---

## Features

- Aircraft tracking
- Maritime traffic monitoring
- Satellite tracking
- Global event visualization
- GPS interference detection

---



## Installation

Clone the repository:

git clone https://github.com/z1000biker/shadowbrokergr.git  
cd shadowbrokergr

Run with Docker:

docker compose up -d

Open in browser:

http://localhost:3000

---

## Project Structure

shadowbrokergr
- frontend
- backend
- docs
- docker-compose.yml
- README.md

---


## Getting Started

### Prerequisites
- Node.js (v18+)
- Python 3.10+
- Mapbox Access Token (for the base map)

### Installation

1. **Backend Setup**
   Navigate to the `backend` directory, install dependencies, and run the server:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\Activate.ps1
   pip install -r requirements.txt
   python main.py
   ```

2. **Frontend Setup**
   Navigate to the `frontend` directory, install Node packages, and run the development server:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

3. **Application Access**
   Open `http://localhost:3000` in your browser. Complete the onboarding to add your own OpenSky and AIS Stream free API keys for full data layer functionality.

---
*Based on the Shadowbroker project created by BigBodyCobain.*
## License

MIT
