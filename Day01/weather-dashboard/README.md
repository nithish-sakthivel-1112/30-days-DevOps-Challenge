Day 1 - 30 Day DevOps Challenge by Cozy Cloud

Weather Dashboard

Warm-up to the Month-Long DevOps Challenge

Technologies Used

Python

AWS S3

Objective

Connect to an S3 bucket via Python and store JSON files in it.

Fetch weather details using a basic API GET call from the OpenWeather API.

Flow

1. API Provider

Create an account on OpenWeather.

Generate an API key from the OpenWeather API dashboard.

2. Project Structure

weather-dashboard/
├── src/
│   ├── __init__.py
│   └── weather_dashboard.py
├── .env
├── .gitignore
├── requirements.txt
└── README.md

3. GitIgnore

Use a .gitignore file to ignore sensitive files and unnecessary code artifacts. Examples:

Environment variable files (.env).

Python bytecode files (__pycache__/).

4. Environment File

Create a .env file in your project directory to store sensitive information securely. Example:

OPENWEATHER_API_KEY=your_openweather_api_key
AWS_BUCKET_NAME=weather-dashboard-unique
AWS_ACCESS_KEY_ID=your_aws_access_key_id
AWS_SECRET_ACCESS_KEY=your_aws_secret_access_key
AWS_DEFAULT_REGION=your_aws_default_region

5. Code

The Python code for the weather dashboard handles API calls, S3 bucket interactions, and JSON storage.

See the source code for implementation details.

How to Run

1. Running Python File

Run the Python script directly:

python src/weather_dashboard.py

Resources

OpenWeather API Documentation: Learn more about the OpenWeather API.

AWS S3 Documentation: Comprehensive guide to using AWS S3.

AWS CLI Configuration: Guide to configuring the AWS CLI.

Additional Notes

Ensure your AWS credentials are properly configured before running the project.

Test API connectivity and bucket access permissions to avoid runtime errors.

Use logging in the Python script to replace print statements for better debugging and log management.

Happy coding and learning DevOps!

