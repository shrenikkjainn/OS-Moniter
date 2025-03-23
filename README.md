Real-Time System Monitoring

Project Description

This project is a real-time system monitoring application that provides live insights into CPU, memory, and disk usage. The system includes a Flask API, a React frontend, and an HTML dashboard to visualize system performance. Additionally, it features anomaly detection using the Isolation Forest algorithm and includes pytest-based testing for the API.

Features

Live System Metrics: Fetches real-time CPU, memory, and disk usage.

REST API Endpoint: Provides system status via JSON.

React Frontend: Displays real-time data dynamically.

HTML Dashboard: Interactive UI with animated progress bars.

Anomaly Detection: Uses Isolation Forest to identify abnormal CPU usage.

Automated Testing: Pytest-based tests for API reliability.

Technologies Used

Backend: Flask (Python-based API)

Frontend: React.js & HTML Dashboard

System Monitoring: psutil (for retrieving system metrics)

Machine Learning: Isolation Forest (for anomaly detection)

Testing: Pytest

API Format: JSON-based REST API

Installation

Clone the repository:

git clone https://github.com/your-repo/system-monitoring.git

Install dependencies:

cd system-monitoring
pip install -r requirements.txt  # For Flask backend
npm install  # For React frontend

Run the Flask backend:

python app.py

Run the React frontend:

npm run dev

Open the HTML dashboard (index.html) in a browser.

API Endpoint

GET /api/system_status

Returns real-time system statistics in JSON format:

{
  "cpu_usage": 45.5,
  "memory_usage": 65.2,
  "disk_usage": 72.8
}

Future Enhancements

Web-based Dashboard for visualization

Alert system for high resource usage

Authentication and role-based access control

Historical data analysis and logging

Contributors

Your Name (@your-github)

License

This project is licensed under the MIT License.

