# Cloud CI/CD Beginner Assignment

# Student Information
Name: Amna H.Z Moqat.
Course: Cloud Computing


#  What is CI/CD?

Continuous Integration (CI) is a development practice where code changes are automatically validated whenever a new update is pushed to the repository.  
This helps detect issues early and ensures that the project files remain consistent.

Continuous Deployment (CD) extends this process by automatically publishing the application after successful validation.  
In this project, GitHub Actions performs both tasks by running a workflow that checks the project files and then deploys the website to GitHub Pages.

# My Pipeline

In this project, the CI/CD pipeline is triggered whenever a change is pushed to the **main branch**.

First, GitHub Actions runs the workflow defined in `deploy.yml` and performs a basic validation step to ensure that the required files exist (`index.html`, `style.css`, and `script.js`).  
If the validation succeeds, the workflow automatically deploys the website to **GitHub Pages**, making the latest version available online.

This means that every update pushed to the repository is automatically reflected on the live website without manual deployment.


# Live Website
[https://amnamuqat.github.io/cloud-beginner-cicd-pages-amna./]


# Demonstration Video
[https://youtu.be/pTdQzKyU4JE]


## How to Run the Project Locally
1. download the repository.
2. Open `index.html` in any web browser.
3. The website will load with its styles and JavaScript functionality.
