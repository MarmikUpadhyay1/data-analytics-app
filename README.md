
# Data Analytics App
### Assignment #4: Python-Based Data Analytics Application Deployment


## Objective
The aim of this project is to create a Python-based data analytics application and set up a fully automated CI/CD pipeline. This pipeline will handle building, testing, deploying, and monitoring the application with tools like Docker, Kubernetes (Minikube), and Jenkins.

---

## Technologies Used
- **Version Control**: GitHub
- **Containerization**: Docker
- **Orchestration**: Minikube (Kubernetes)
- **CI/CD Tool**: Jenkins
- **Testing Tools**: Pytest, Selenium (optional for UI testing)
- **Configuration Management**: Ansible or Chef
- **Monitoring**: AWS CloudWatch (optional)

---


## Steps to Complete the Project

### 1. GitHub Setup
- Create a GitHub repository to host the project.
- Set up folders for source code, tests, data, Kubernetes manifests, and documentation.
- Add a sample dataset in the `data` folder.
![e66fff95-7b85-41b2-9f79-39797d0c5873](https://github.com/user-attachments/assets/4949cf19-7a1e-4f47-86bc-212eb211e32b)

### 2. Develop the Python Application
- Build a Python application with modular, reusable code.
- Use a virtual environment to manage dependencies.
- Implement key data analytics features.
![2253c8f8-8c83-4428-be63-09c1d9e1217e](https://github.com/user-attachments/assets/105f0f7b-d1a4-4da6-8a99-a26c456e64ca)

### 3. Containerization
- Write a `Dockerfile` to containerize the app using a lightweight Python base image.
- Include dependencies and ensure the application is ready to deploy.

### 4. CI/CD Pipeline with Jenkins
- Automate the workflow with Jenkins:
  - Build the Python app and install dependencies.
  - Run unit tests to ensure correctness.
  - Build and push the Docker image.
  - Deploy the app to Kubernetes.
![366cb22f-e444-4dfd-8d7b-1d9e5cfe2f12](https://github.com/user-attachments/assets/9724bdca-31a2-478f-ac3c-74ac52ad5b08)
![c6720583-9fd8-44da-a0da-3769927455af](https://github.com/user-attachments/assets/7f6bf5a4-8d2c-4bd0-940c-4e012c8d28a8)

### 5. Testing
- Write unit tests with Pytest to validate the analytics functionality.
- Optionally, write Selenium tests for any web-based interfaces.

### 6. Deploy with Minikube
- Deploy the app to a local Kubernetes cluster using Minikube.
- Write Kubernetes manifests for deployment and services.
![68fab6b1-4770-4713-b295-f021fce3b72b](https://github.com/user-attachments/assets/6b7af2f8-a0a5-4c9b-897a-521575f42bbf)

### 7. Configuration Management
- Use Ansible or Chef to automate server and app setup tasks.
- Set up Docker, Kubernetes, and deploy manifests.
![17c7c997-e924-40f0-a02e-a119826b30ea](https://github.com/user-attachments/assets/cfb5543c-2ce9-463d-87bb-46dc8c2a57d9)

### 8. Monitoring (Optional)
- Set up AWS CloudWatch to monitor the application.
- Visualize performance metrics and logs.
- ![7838a503-fa94-4ac1-ba27-fcb6e73bfc04](https://github.com/user-attachments/assets/35b36f89-48c9-4b0a-8e4a-a05538bd37da)


---

## Deliverables
1. **GitHub Repository**: All project files, including the Dockerfile, Jenkinsfile, Kubernetes manifests, and Ansible scripts.
2. **Documentation**: A clear README file with setup instructions and pipeline details.
3. **Presentation**: Highlight the workflow, challenges, and solutions implemented.

---

## How to Run the Application
1. Clone the repository from GitHub.
2. Build the Docker image using the provided Dockerfile.
3. Run the container locally or deploy the app to Kubernetes using Minikube.
4. Test the application functionality with the provided scripts.

---

## Evaluation Criteria
- Clean and modular code with appropriate documentation.
- Fully functional CI/CD pipeline.
- Comprehensive and clear documentation.
- Ability to demonstrate the project effectively.

---

This README provides a simple guide to completing and deploying the application. Customize further based on your specific implementation.
