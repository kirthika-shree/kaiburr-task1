# kaiburr-assignment

Task 1 – Java Backend and REST API
A Spring Boot-based RESTful API to manage "task" objects that include shell commands. Each task allows execution of the command, and the results (start time, end time, output) are stored in MongoDB.

Features:

Create, retrieve, delete, and search tasks

Execute safe shell commands via API

MongoDB as a persistent data store

Tested using Postman

🔹 Task 2 – Kubernetes Deployment
The backend application is containerized using Docker and deployed into a Kubernetes cluster along with MongoDB. The command execution logic is enhanced to run commands inside dynamically created Kubernetes pods using the Kubernetes Java client.

Features:

Separate pods for MongoDB and backend

Persistent volume for MongoDB

Application exposed via NodePort

Task execution inside isolated busybox pods

🔹 Task 3 – Web UI with React, TypeScript, Ant Design
A modern and responsive frontend built using React 19, TypeScript, and Ant Design. The UI interacts with the backend to manage tasks.

Features:

Create, view, search, and delete tasks

Execute tasks and view output

User-friendly interface

Clean and accessible design

🔹 Task 4 – CI/CD Pipeline
A CI/CD workflow is created using GitHub Actions to automate code build and Docker image generation for the backend application.

Features:

Automated build on every push

Docker image built and optionally pushed to DockerHub

Can be extended for Kubernetes deployment

🔹 Task 5 – Text Classification (Data Science)
A machine learning project to classify consumer complaints into categories using text data from data.gov.

Features:

Text preprocessing and feature extraction

Model comparison: Logistic Regression, Naive Bayes

Evaluation using accuracy, confusion matrix

Final model predicts complaint categories like Debt Collection, Mortgage, etc.

