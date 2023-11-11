# django-aws-tier-3-GH-action

## Overview
This repository demonstrates the design and visualization of a 3-tier architecture for deploying a Django REST API on AWS using GitHub Actions.

## Prerequisites
- Python and Django installed locally.
- An AWS account with necessary permissions.
- Basic knowledge of GitHub Actions.
- AWS Elastic Beanstalk CLI (`eb`) installed locally.


## Getting Started
Follow these steps to set up and run the project locally:

1. Clone this repository:

    ```bash
    git clone https://github.com/Kunal2703/django-aws-tier-3-GH-action.git
    ```
2. Navigate to the project directory: 
  ```sh
  cd django-aws-tier-3-GH-action
  ```
3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```
4. Apply migrations:

    ```bash
    python manage.py migrate
    ```
5. Run the development server:

    ```bash
    python manage.py runserver
    ```
 > Visit http://127.0.0.1:8000/ in your web browser to ensure the project is running locally.

## Deployment to AWS Elastic Beanstalk via GitHub Actions
The project includes a GitHub Actions workflow (`/.github/workflows/main.yml`) for continuous integration and deployment.

Follow these steps for AWS Elastic Beanstalk deployment:

1. Set up your AWS Elastic Beanstalk environment.

2. Configure your AWS Elastic Beanstalk environment variables in your GitHub repository settings.

3. Push your changes to the main branch. GitHub Actions will automatically trigger the deployment workflow.


## Application Link

View the deployed application at (http://django-env.eba-rtnac2xc.us-west-2.elasticbeanstalk.com/).


