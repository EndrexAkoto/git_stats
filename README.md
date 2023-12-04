Git Stats
Overview

Git Stats is a web application that fetches data from GitHub repositories, providing insights into user details, repository information, and commit history.
Features

    GitHub Data Fetching: Fetches user data, repository details, and commit information from GitHub using the GitHub API.

    Web Interface: Presents the fetched data through a user-friendly web interface.

    CSV Export: Exports fetched data into CSV files for further analysis.

Project Structure

The project is organized into the following components:

    Backend: Handles data fetching and serves the API endpoints.
        backend/app.py: Flask application for serving the API.
        backend/github_data_fetcher.py: Module for fetching data from the GitHub API.

    Frontend: Provides a web interface for users to interact with the fetched data.
        frontend/index.html: Main HTML file.
        frontend/scripts.js: JavaScript file for handling frontend logic.

Getting Started

    Clone the Repository:

    bash

git clone https://github.com/your-username/git_stats.git
cd git_stats

Install Dependencies:

bash

pip install -r backend/requirements.txt

Run the Application:

bash

# Start the backend server
cd backend
python app.py

Open a new terminal window:

bash

    # Start the frontend server
    cd frontend
    live-server

    Access the application at http://127.0.0.1:8080.

Usage

    Visit http://127.0.0.1:8080 in your web browser to interact with the Git Stats application.

    API Endpoint: http://127.0.0.1:5000/api/data for fetching GitHub data.

Known Issues

    The project currently faces issues related to fetching data from GitHub. Please refer to the project's issue tracker for updates.

Authors

The only author of this project EndrexAkoto
