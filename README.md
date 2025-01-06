# 30 Days DevOps Challenge - Weather Dashboard

As part of the **30 Days DevOps Challenge**, I embarked on creating a **Weather Data Collection System** to solidify my understanding of core DevOps principles. On **Day 1**, I focused on building a robust system that integrates external APIs with cloud storage, manages environment variables securely, and utilizes version control effectively.

# Weather Data Collection System - DevOps Day 1 Challenge

## Project Overview
This project is a Weather Data Collection System that demonstrates core DevOps principles by combining:
- External API Integration (OpenWeather API)
- Cloud Storage (AWS S3)
- Infrastructure as Code
- Version Control (Git)
- Python Development
- Error Handling
- Environment Management

## Features
- Fetches real-time weather data for multiple cities
- Displays temperature (°F), humidity, and weather conditions
- Automatically stores weather data in AWS S3
- Supports multiple cities tracking
- Timestamps all data for historical tracking

## Technical Architecture
- **Language:** Python 3.x
- **Cloud Provider:** AWS (S3)
- **External API:** OpenWeather API
- **Dependencies:** 
  - boto3 (AWS SDK)
  - python-dotenv
  - requests

## Project Structure
weather-dashboard/
├── src/
│   ├── init.py
│   └── weather_dashboard.py
├── tests/
├── data/
├── .env
├── .gitignore
└── requirements.txt
Copy
## Setup Instructions
1. Clone the repository:
--bash
git clone https://github.com/ShaeInTheCloud/30days-weather-dashboard.git

3. Install dependencies:
bashCopypip install -r requirements.txt

4. Configure environment variables (.env):
CopyOPENWEATHER_API_KEY=your_api_key
AWS_BUCKET_NAME=your_bucket_name

4.Configure AWS credentials:
bashCopyaws configure

5. Run the application:
python src/weather_dashboard.py

What I Learned

AWS S3 bucket creation and management
Environment variable management for secure API keys
Python best practices for API integration
Git workflow for project development
Error handling in distributed systems
Cloud resource management

Outputs:
![image](https://github.com/user-attachments/assets/a4668566-d904-4422-b47d-370fd33a8860)
![image](https://github.com/user-attachments/assets/07887fa9-0f72-4998-936e-2a8913f70803)
![image](https://github.com/user-attachments/assets/8e550187-eba9-4591-bb49-115a60ef7e99)



