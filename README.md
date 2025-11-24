# weather---alert---system
Python-based Weather Alert System for VITyarthi – Build Your Own Project. 

PROJECT STRUCTURE 

✅ Problem Statement
✅ All Functional & Non-functional Requirements
✅ Architecture Diagram
✅ Use Case Diagram
✅ Workflow Diagram
✅ Class Diagram
✅ Sequence Diagram
✅ ER Diagram
✅ Full project report
✅ README.md + statement.md 


# Weather Alert System

Small Python application to generate user-friendly weather alerts.

## Features
- Online mode (OpenWeatherMap) and offline mode (CSV sample).
- Rule-based alert generation: Normal / Moderate / Severe.
- Logs alerts to alerts.log and saves per-run report to reports/.

## Setup
1. Create venv: python -m venv venv and activate.
2. pip install -r requirements.txt
3. (Optional) Get OpenWeatherMap API key and run:
   python main.py "Pune" --api-key YOUR_KEY
4. Offline mode: python main.py "Pune" --offline --csv sample_data/sample_weather.csv

## Tests
pytest tests
# Project Statement

*Problem statement:* Users require simple, actionable weather alerts rather than raw data.
*Scope:* Input city & weather parameters -> rule-based processing -> alert & suggestions.
*Target users:* Students, commuters, event organisers.
*High-level features:* Online/offline data ingestion, rule-based alerts, logging & reporting. 

RESULTS 
The model shows accuracy and precise weather after the required info been given
