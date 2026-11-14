# 🚀 Mission Trainer
### Interactive Space Mission & Rocket Launch Simulation

🌐 **Live Website:** https://nasaproject-xi.vercel.app/

## 🌍 About the Project

Mission Trainer is an interactive, child-friendly space mission simulation platform developed for the NASA Space Apps Challenge 2026. It helps young learners understand rocket science and space exploration through interactive 3D visualization and simplified mission simulations.

## ✨ Features

- Interactive 3D visualization of Earth, Moon, and Mars.
- Earth daytime and nighttime imagery.
- City-based launch location selection.
- International Space Station (ISS) live position tracking.
- Space destination and orbit selection.
- Rocket configuration with fuel, mass, thrust, power, payload, and budget.
- Multiple engine options: Kerolox, Methalox, and Hydrolox.
- Multi-stage rocket configuration (1–4 stages).
- Delta-v and mission feasibility analysis.
- Animated rocket launch simulation.
- Mission success or failure results.

## 🛰️ NASA Data Integration

**1. NASA GIBS – Global Imagery Browse Services**
- Blue Marble Next Generation – Earth daytime imagery.
- VIIRS Black Marble – Earth nighttime lights.

Documentation: https://nasa-gibs.github.io/gibs-api-docs/

**2. NASA EPIC API**

Retrieves available Earth observation image metadata and related information.

API: https://epic.gsfc.nasa.gov/api/natural

Documentation: https://epic.gsfc.nasa.gov/about/api

**3. ISS Live Tracking**

Uses the third-party WhereTheISS.at API to retrieve the International Space Station's live position.

API: https://api.wheretheiss.at/v1/satellites/25544

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Three.js
- WebGL
- NASA GIBS WMS
- NASA EPIC API
- WhereTheISS.at API

## ▶️ Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/sakib6065pks-blip/NASA_Project.git
   ```

2. Open the project folder.

3. Run a local server:

   ```bash
   python -m http.server 8000
   ```

4. Open your browser and visit:

   `http://localhost:8000`

An internet connection is required for external APIs, libraries, and remote imagery.

## 🎯 Project Goal

Our goal is to make space science more accessible and engaging for children and students by transforming complex rocket mission concepts into an interactive learning experience.

## 🚀 Future Improvements

- Integration of additional verified Mars datasets.
- More realistic planetary environments.
- Improved rocket physics and mission calculations.
- Additional interactive space missions and educational challenges.

## 👥 Team

**Team Titan BD**

NASA Space Apps Challenge 2026

---

**Mission Trainer – Explore Space. Understand Science. Launch Your Curiosity!**
