# Algebra Genius

**Empowering students to master Algebra 1 through AI-driven, step-by-step guidance.**

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

**Algebra Genius** is an interactive web application designed to assist students in solving Algebra 1 problems. Leveraging advanced AI models, the platform provides step-by-step solutions, verifies answers using the Wolfram Alpha API, and tracks user progress to offer personalized learning experiences.

## Features

- **AI-Powered Problem Solving:** Utilizes Large Language Models (LLMs) to guide students through Algebra 1 problems.
- **Answer Verification:** Integrates with the Wolfram Alpha API to ensure solution accuracy.
- **Progress Tracking:** Stores user interactions and progress using Firebase Realtime Database.
- **User Authentication:** Implements Firebase Authentication for personalized experiences.
- **Responsive Design:** Built with React.js for seamless use across various devices.

## Demo

[Provide a link to a live demo or include screenshots/gifs showcasing the application's interface and functionality.]

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/algebra-genius.git
2. **Navigate to the project directory:**
   cd algebre-genius
3. **Install frontend dependecies**
   cd frontend
   nmp install
4. **Install backend dependencies:**
   cd ../backend
   pip install -r requierements.txt
## Usage
1. Set up environment variables:
     - **Create a .env file in the backend directory with the following variables:
       WOLFRAM_ALPHA_APP_ID=your_wolfram_alpha_app_id
       FIREBASE_API_KEY=your_firebase_api_key
       FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
       FIREBASE_DATABASE_URL=your_firebase_database_url
       FIREBASE_PROJECT_ID=your_firebase_project_id
       FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
       FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
       FIREBASE_APP_ID=your_firebase_app_id
2. Start the backend server:
   cd backend
   python app.py
3. Start the frontend application:
   cd frontend
   npm start
4. Access the application:
   Open http://localhost:3000
