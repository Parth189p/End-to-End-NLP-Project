# Text Summarization using Transformers

Welcome to the Text Summarization project, a comprehensive NLP project that demonstrates end-to-end machine learning capabilities, including model building, training, and deployment. The project showcases its potential for scalability and production-level deployment by incorporating CI/CD pipelines on GitHub Actions, Docker, and deployment on both AWS and Azure.

## Project Overview

This NLP project focuses on text summarization using state-of-the-art Transformers. Key highlights of the project include:

- **Model Building:** The project employs PyTorch and transfer learning, using Google's Pegasus model for text summarization. The dataset used is the SAMSUN database.

- **MLOps Pipeline:** The project follows object-oriented programming principles and consists of various pipelines, including data ingestion, data validation, data transformation, model training, model evaluation, and prediction.

- **Custom Log File:** A custom log file structure is implemented for efficient debugging and error tracking.

- **Flask Web App:** A web application is created using Streamlit to provide a user-friendly interface for text summarization.

- **Docker Deployment:** The project is containerized using Docker for seamless deployment and scaling.

- **CI/CD Pipeline:** GitHub Actions is used to create a Continuous Integration and Continuous Deployment (CI/CD) pipeline, automating the project's build, test, and deployment processes.

- **Cloud Deployment:** The project is deployable on both AWS and Azure, highlighting its cloud compatibility.

## Getting Started

Here's how to get started with the Text Summarization project:

### Prerequisites

- Python 3.11
- PyTorch
- Transformers (Hugging Face)
- Streamlit
- Docker


### Workflow

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. update the conponents
6. update the pipeline
7. update the main.py
8. update the app.py

### Installation

```bash
# Clone this repository
git clone https://github.com/Parth189p/End-to-End-NLP-Project.git

# Install project dependencies
pip install -r requirements.txt

# Run the project
python main.py

# If you want to run the Flask app
python app.py

```

## Next steps in project to do

## Deployment Steps

### AWS CI/CD Deployment with GitHub Action

1. Login to AWS console 
2. Creat I AM user 
3. Creat ECR repo to store
4. Creat EC2 machine
5. Install docker in EC2 machine
6. Configure EC2 as self-hostged runner
7. Setup git-hub secrets



