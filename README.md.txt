# Engine Health Monitoring System

## 🚀 Quick Start

### Installation
1. Open Command Prompt / Terminal
2. Navigate to this folder:
   ```cmd
   cd Desktop\engine-health
Install required packages:

Install required packages:
cmd
pip install -r requirements.txt

Run the application:
cmd
streamlit run engine_monitor.py

Open your browser to: http://localhost:8501
 Test Scenarios
Scenario	Temperature	Vibration	Oil Pressure	Expected Result
Normal Operation	85°C	10 Hz	50 psi	No problems detected
Overheating	100°C	11 Hz	48 psi	Overheating warning
Engine Imbalance	85°C	15 Hz	50 psi	Vibration warning
Low Oil Pressure	90°C	10 Hz	35 psi	Low pressure warning

📊 System Pages
Engine Health Dashboard - Overall health score and predictive insights

Live Input - Enter sensor readings and get real-time analysis

Overview - View historical trends and statistics

Settings - Configure normal ranges and system tools

🛠️ Technology Stack
Framework: Streamlit (Web Interface)

Data Processing: Pandas, NumPy

Visualization: Plotly

Analysis: Custom Rule-Based Engine

📁 Project Structure
text
engine-health/
├── engine_monitor.py      # Main application
├── requirements.txt       # Python dependencies
└── README.md             # This file
🤔 Troubleshooting
"pip is not recognized": Use python -m pip install -r requirements.txt

File not found: Make sure you're in the correct folder (Desktop\engine-health)

Port already in use: Streamlit will automatically use another port (8502, 8503, etc.)

📞 Support
For questions or issues, contact: rainiermagpantay01@gmail.com

