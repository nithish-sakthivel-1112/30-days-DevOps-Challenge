# Day 1 - 30 Day DevOps Challenge by Cozy Cloud

## Weather Dashboard

This application fetches weather app data from the OpenWeather API and saves it to AWS S3 Bucket. The application. The application is containerized using Docker.

## Prerequisites
- python installed on the system
- vscode
- AWS account with access keys
- OpenWeather API key

## Setup

1. Clone this repository:
    ```sh
    git clone https://github.com/nithish-sakthivel-1112/30-days-DevOps-Challenge.git
    cd weather-dashboard
    ```

2. Create a [.env]file in the root directory with the following content:

    ```properties
      OPENWEATHER_API_KEY=your_openweather_api_key
      AWS_BUCKET_NAME=weather-dashboard-${RANDOM}
      # AWS CREDENTIALS
      AWS_ACCESS_KEY_ID=your_aws_secret_key_id
      AWS_SECRET_ACCESS_KEY=your_aws-secret_access_key
      AWS_DEFAULT_REGION=your_aws_default_region
    ```


## Usage 

The application will fetch weather data from the cities added into the json file at **/data/cities.json** file. The weather data will be saved to the specified AWS S3 bucket.

## AWS Configuration

The application uses the AWS CLI to interact with the S3. Ensure your AWS credentials are correctly set in the **.env** file.

## Outputs
Execute python3 src/weather-dashboard.py
![image](https://github.com/user-attachments/assets/5d5cd88c-464f-4359-88c3-fd73b9372f96)

![image](https://github.com/user-attachments/assets/6c37a3a8-22a2-4537-ae7d-7994999cc0ca)


## Resources
- [OpenWeather API Documentation](https://openweathermap.org/api): Learn more about the OpenWeather API.
- [AWS S3 Documentation](https://docs.aws.amazon.com/s3/index.html): Comprehensive guide to using AWS S3.
- [AWS CLI Configuration](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html): Guide to configuring the AWS CLI.

## License 

This project is licensed under the MIT License.


Thanks to <a id='ShaeInTheCloud' href="https://github.com/ShaeInTheCloud">ShaeInTheCloud</a>
