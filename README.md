

Traditional monitoring systems mostly depend on manual checking or fixed rules to identify problems in system logs. These methods can miss important patterns and may not respond quickly to failures.

This project improves the monitoring process by automatically analyzing incoming logs and identifying whether a system failure is likely to occur. The workflow processes logs in real time, makes predictions, and triggers automated actions without manual intervention.

## Key Advantages

- Reduces manual monitoring effort
- Detects issues faster
- Helps prevent unexpected system downtime
- Improves reliability of applications and servers
- Automates logging and monitoring tasks
- Supports real-time decision making

## Workflow Impact

1. Logs are received through a webhook
2. The logs are processed through the prediction system
3. The workflow checks the prediction result
4. Important events are automatically recorded in Google Sheets
5. The system creates a smooth automated monitoring pipeline

## Real-World Applications

- Server health monitoring
- Infrastructure management
- Application failure detection
- Predictive maintenance systems
- DevOps and IT operations automation
# Tech Stack

## Programming & Data Processing
- Python
- Pandas
- NumPy

## Model Development
- Scikit-learn
- Joblib / Pickle

## API & Backend
- FastAPI
- Uvicorn

## Automation Workflow
- n8n

## Storage & Logging
- Google Sheets API

## Development Environment
- Jupyter Notebook
- VS Code

## Deployment & Version Control
- Git
- GitHub

This project demonstrates how intelligent automation can be used to build efficient and scalable real-time monitoring systems.

<img width="1454" height="917" alt="image" src="https://github.com/user-attachments/assets/e22fd615-88de-423d-b669-021fb0d8d015" />
