# Pipeline Sentinel 🛢️

**An AI-Powered Pipeline Leak Detection Dashboard**

Pipeline Sentinel is a frontend simulation of an industrial mission-control dashboard. It visualizes how field operators would monitor and respond to AI-driven leak alerts in real time. This was built as a capstone project during my AI and Machine Learning internship.

## 🎯 Project Overview

In industrial pipeline monitoring, distinguishing between normal operational transients and actual leaks is a massive challenge. This project bridges the gap between complex machine learning logic and actionable operational interfaces. It simulates data streaming from pipeline sensors and visualizes the inference results of ensemble AI models.

## ✨ Key Features

* **Real-Time Data Visualization:** Live, animated charting of pressure, flow rate, temperature, and acoustic sensor data using Vanilla JavaScript and HTML5 Canvas.
* **Ensemble AI Simulation:** Visual representation of leak probabilities from a supervised model (LSTM time-series classifier) and reconstruction errors from an unsupervised model (Autoencoder).
* **Physics-Based Localization:** Uses Negative Pressure Wave (NPW) calculations to estimate and display the physical location of a pipeline breach.
* **Mission-Control UI/UX:** A high-contrast, dark-mode interface designed to minimize alert fatigue while ensuring critical operational alarms are immediately visible.
* **Interactive Controls:** Built-in operator controls to simulate leak events, pause live monitoring, and clear system logs.

## 🛠️ Technology Stack

* **HTML5:** Semantic structure and layout.
* **CSS3:** Custom styling, CSS variables, grid/flexbox layouts, and keyframe animations.
* **JavaScript (ES6):** State management, DOM manipulation, random noise generation for sensor baselines, and Canvas API charting.

## 🚀 How to Run

Since this project is built entirely with client-side web technologies, no build tools or servers are required.

1. Clone this repository or download the `pipeline-sentinel.html` file.
2. Double-click the file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Click the **Simulate Leak** button to watch the system transition from normal operations to an alarm state.

## 👨‍💻 Author

**Bamidele Stephen**
Feel free to connect with me on LinkedIn to discuss UI/UX design, frontend development, or industrial AI applications!
