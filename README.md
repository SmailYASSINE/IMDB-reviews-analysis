# IMDB-reviews-analysis

Overview
This project focuses on sentiment analysis of IMDb movie reviews, employing a diverse set of machine learning models. It includes data preprocessing, model training, deployment as REST APIs using FastAPI and Flask, and containerization with Docker. The project emphasizes best practices in modern machine learning and web development.

Project Structure
app/
fastApp/
Contains the FastAPI application code.
flask app/
Contains the Flask application code.
notebook/
Contains the most important processing technics for training model

Usage

Prerequisites
Docker installed
Python 3.7+
Running the Project
Clone the repository:

bash
code
git clone https://github.com/your-username/sentiment-analysis-project.git
cd sentiment-analysis-project
Build and run the Docker containers:

bash
Copy code
docker-compose up --build
This will start both the FastAPI and Flask applications in parallel.

Access the FastAPI application at http://localhost:8000 and the Flask application at http://localhost:5000.

API Endpoints
FastAPI:

Base URL: http://localhost:8000
Endpoint for predictions: /predict
Flask:

Base URL: http://localhost:5000
Endpoint for consuming the FastAPI predictions: /consume
Customization
Feel free to customize the project by modifying the machine learning models, dataset, or application code. Explore the docker-compose.yml file, Dockerfiles, and application configurations for further adjustments.
