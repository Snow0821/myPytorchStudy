# MyPytorchStudy

## Introduction

This project utilizes PyTorch within a Docker environment to streamline the setup for machine learning experiments, focusing on aspects such as model training, data preprocessing, and result postprocessing.

## Getting Started

### Prerequisites

-  Docker
-  Docker Compose
-  Git

### Setup Instructions

1. **Clone the Repository**

   Clone the repository to your local machine to get started:

```
   git clone git@github.com:Snow0821/myPytorchStudy.git
   cd MyPytorchStudy
```

2. **Build and Run with Docker Compose**

   In the project root directory, use Docker Compose to build and run your container:

```
   docker-compose up --build
```

This builds the Docker image from the Dockerfile if needed and runs the main Python script (main.py) within the Docker container.

## Project Structure

-  app/: Contains the Python code for model training and inference.
-  input/: Directory at the root level for storing input data.
-  output/: Directory at the root level for saving output models and results.
-  Dockerfile: Specifies how to build the Docker image.
-  docker-compose.yml: Contains Docker Compose configurations for straightforward project execution.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
