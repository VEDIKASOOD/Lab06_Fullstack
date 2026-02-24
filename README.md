Lab 06 – Full Stack Web Application Setup
Student Details

Name: Vedika Sood

Roll No: CS-23411111

Course: B.Tech Computer Science & Engineering

Subject: Web Technologies

Lab Number: 06

College: IILM University

Faculty Name: Mr. Dibyanarayan Hazra


Objective of the Experiment

The objective of this experiment is to understand and implement the basic structure of a full stack web application.
The project demonstrates how frontend and backend components are organized separately, how dependencies are managed, and how version control is applied using Git and GitHub.

Project Overview

This project contains the skeleton structure of a full stack web application with:

A backend folder for server-side development using Node.js and Express.

A frontend folder for client-side development using React with Vite.

A Git repository for version control and submission.

The actual business logic will be extended in future experiments.

Project Folder Structure

my app lab 6 wt/
│
├── backend/
│   ├── src/
│   │   └── server.js
│   ├── package.json
│   └── package-lock.json
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── README.md
│   ├── package.json
│   └── vite.config.js
│
├── .gitignore
└── README.md

Backend Setup (Step-by-Step)

Step 1: Navigate to Backend Folder
cd backend
Step 2: Initialize Node.js Project
npm init -y

This command creates the package.json file which stores project metadata and dependencies.

Step 3: Install Required Backend Dependencies
npm install express cors dotenv
npm install -D nodemon

express – used to create the backend server

cors – allows frontend-backend communication

dotenv – manages environment variables

nodemon – restarts server automatically during development

Step 4: Create Backend Server File

A file named server.js is created inside the src folder.
This file contains the Express server configuration and a test route to verify server execution.

Step 5: Run Backend Server
node src/server.js

On successful execution, the terminal displays:

Server running on port 3000

Frontend Setup (Step-by-Step)
Step 6: Navigate to Frontend Folder
cd frontend
Step 7: Create React Project Using Vite
npm create vite@latest . -- --template react

Vite is used as it provides faster build time and efficient hot module replacement.

Step 8: Install Frontend Dependencies
npm install
Step 9: Run Frontend Development Server
npm run dev

The frontend runs on:

http://localhost:5173

This confirms successful frontend setup.

README File Placement Explanation

frontend/README.md contains frontend-specific details and student identification.

README.md (this file) explains the entire project workflow, structure, and execution steps.

Both files serve different purposes and are intentionally placed in their respective directories.

Git and GitHub Workflow
Step 10: Initialize Git Repository
git init
Step 11: Add Files to Git
git add .
Step 12: Commit Changes
git commit -m "Lab 06 full stack project setup"
Step 13: Push Project to GitHub
git branch -M main
git remote add origin <repository-url>
git push -u origin main

This uploads the project to GitHub for evaluation and submission.