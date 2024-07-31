T2 : DOCKER CONTAINERIZATION

## Project Description
The Python Calculator App is a simple calculator that supports basic arithmetic operations such as addition, subtraction, multiplication, and division. This project demonstrates the use of Python functions and conditional statements in a command-line interface. The application has been containerized using Docker for easy deployment and scaling.

## Features
- **Basic Arithmetic Operations:** Add, subtract, multiply, and divide two numbers.
- **Error Handling:** Graceful handling of invalid inputs and division by zero.
- **Interactive CLI:** User-friendly command-line interface for input and interaction.
- **Dockerized:** Easy to deploy and run as a Docker container.

## Key Components
1. **Python Script (`calculator.py`):** The core script containing functions for each arithmetic operation and the main logic for user interaction.
2. **Dockerfile:** Defines the Docker image, specifying the base image, working directory, copying the application code, and setting the entry point.
3. **README.md:** Documentation for understanding, setting up, and using the project.

## Installation
To run this project locally, you need to have Docker installed. Follow these steps:

 **Clone the repository:**
   
Build the Docker image:

bash
Copy codeRun the Docker container:

bash

docker run -it --rm python-calculator-app
Usage
After running the Docker container, the application will prompt you to choose an operation:

Add
Subtract
Multiply
Divide
Follow the prompts to enter two numbers and receive the result of the selected operation.

Dockerization
The application is containerized using Docker, allowing it to run consistently across different environments. The Dockerfile uses a lightweight Python base image and sets up the necessary environment to run the Python script.

Building the Image:

bash

docker build -t python-calculator-app .
Running the Container:

bash

docker run -it --rm python-calculator-app
