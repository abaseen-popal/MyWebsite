# My Flask Website

Welcome to My Flask Website! This is a simple web application built using Flask, a lightweight web framework for Python.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction

My Flask Website is a basic web application that demonstrates how to use Flask to build a simple backend for a website. It provides an example of setting up routes, handling HTTP requests, and serving static files using Flask.

## Features

- Simple "Hello, World!" route
- Easy-to-understand Flask application structure
- Dockerfile for containerization
- Kubernetes manifests for deployment on Kubernetes

## Setup

To set up the project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/abaseen-popal/my-flask-website.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

To run the Flask application locally, execute the following command:
   ```
   python app.py
   ```
   Then, open a web browser and navigate to http://localhost:5000 to view the application.

## Deployment

To deploy the Flask application on Kubernetes, follow these steps:

1. Build the Docker image:
   ```
   docker build -t my-flask-app .
   ```

2. Apply Kubernetes manifests:
   ```
   kubectl apply -f deployment.yaml
   kubectl apply -f service.yaml
   ```

3. Expose the Flask application to external traffic using Ingress or Service's NodePort/LoadBalancer.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
