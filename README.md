# ML Application with Docker

## Overview
This project is a simple machine learning application that leverages Flask to serve predictions based on a trained decision tree classifier. The model is trained using the Iris dataset, which is a classic dataset for classification tasks in machine learning. This application is containerized using Docker for easy deployment and scalability.

## Technologies Used
- Python
- Flask
- scikit-learn
- Docker
- Git

## Project Structure
The project contains the following files:
- `Dockerfile`: Defines the environment for the application.
- `requirements.txt`: Lists the required Python packages.
- `train_model.py`: Script to train the decision tree classifier and save the model.
- `app.py`: Flask application that serves predictions.
- `model.pkl`: The trained machine learning model.

## Instructions to Build and Run the Docker Container

### Prerequisites
- Docker installed on your machine.
- Basic knowledge of how to use the command line.

### Steps to Build the Docker Image
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ml-app.git
   cd ml-app
