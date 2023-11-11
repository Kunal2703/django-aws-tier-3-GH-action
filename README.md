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

2.  Navigate to the project directory: 
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


