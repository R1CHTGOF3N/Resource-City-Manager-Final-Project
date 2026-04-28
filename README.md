# ARIS — Almaty Resource Intelligence System

An AI-powered city resource management dashboard for Almaty, Kazakhstan.
Built with HTML/CSS/JS and powered by the Groq API (Llama 3.3).

## Features
- Real-time monitoring of 6 city resources (water, power, grain, fuel, medical, agriculture)
- 5 crisis scenario simulations (drought, flood, budget shortfall, etc.)
- AI recommendations powered by Groq's Llama 3.3
- District map visualization of Almaty
- Analytics charts based on real Kazakhstan open data

## Data Sources
- [data.egov.kz](https://data.egov.kz) — Citizens' appeals & sectoral data
- [budget.egov.kz](https://budget.egov.kz) — City budget 2024
- [stat.gov.kz](https://stat.gov.kz) — Population statistics

## Setup
1. Get a free API key from [console.groq.com](https://console.groq.com)
2. Open `ARIS_groq.html` in a text editor
3. Replace `YOUR_GROQ_API_KEY_HERE` with your key
4. Open the file in your browser

## Usage
- Click a **crisis scenario** on the left to simulate an emergency
- Type a question in the console (e.g. *"Redistribute water to Ile district"*)
- View AI decisions and resource updates in real time
