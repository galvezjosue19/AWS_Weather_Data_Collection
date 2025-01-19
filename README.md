Weather Dashboard Project AWS

WHAT ARE WE BUILDING? This project is about fetching real-time weather data for multiple cities, displaying temperature, humidity,and weather conditions. It automatically stores the data in AWS S3 bucket with timestamps for historical tracking, supporting efficient monitoring across multiple locations.

PROJECT COMPONENTS:

Open Weather API Integration
AWS S3 Block Storage
Infrastructure as Code
Version Control (Git)
Python Development
Error Handling
Environment Management

System Design:

Language: Python 3.x
Cloud Provider: AWS
External API: OpenWeather API
Dependencies:
boto3 (AWS SDK)
python-dotenv
requests

# Project STructure
![alt text](image.png)


How to set it up
Installed Dependencies
![alt text](image-1.png)

Configured my AWS account with access key and assigned a user full access to S3 buckets.

![alt text](image-2.png)

.Env File configuration
This .env file stores sensitive info like API keys securely, separates configurations from code, and makes it easy to manage environment-specific settings.

![alt text](image-5.png)


RUN PYTHON SCRIPT

type python src/weather_dashboard.py to run the application.

![alt text](image-6.png)


Verify AWS S3 Bucket Data= Success :)

![alt text](image-7.png)



What I Learned

AWS S3 bucket creation and management
Environment variable management for secure API keys
Python best practices for API integration
Git workflow for project development
Error handling in distributed systems
Cloud resource management
