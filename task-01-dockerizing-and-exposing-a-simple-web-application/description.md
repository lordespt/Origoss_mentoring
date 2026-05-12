# Mentoring task 1: Dockerizing and Exposing a simple web application

## Purpose
The purpose of this task is to get the mentee familiar with the basics of microservice architectures and exposing services.

The mentee should choose a frontend and backend project from here:
- Frontend
- Backend

## Prerequisites
- Working local Kubernetes

## Acceptance Criteria
- A new Git repository is created in the Origoss organization containing all manifests and theoretical answers.
- A system diagram representing the deployed architecture is created and added to the repository.
- Both the Frontend and Backend are dockerized according to industry best practices.
- The Backend and the Database are decoupled (i.e., not running in the same pod/deployment. Only applicable if the original project has a coupled backend like SQLite).
- The application runs without errors (missing features or documented bugs should not be fixed or implemented).
- The built docker images are pulled from a registry (either local running in the Kubernetes cluster or ECR or something similar).
- Theoretical questions are answered correctly.