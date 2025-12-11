#Welcome to the ATM Project

Project info

URL: https://github.com/NamishV117/ATM_simulator_flask
How can I edit this code?

There are several ways of editing your application.

Use GitHub

Simply visit the GitHub Project
 and start cloning the repository.

Changes made via GitHub will be committed automatically to this repo.

Use your preferred IDE

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected on GitHub.

The only requirement is having Python, Node.js, and npm installed - install with nvm
.

Follow these steps:

 Step 1: Clone the repository using the project's Git URL.
git clone https://github.com/NamishV117/ATM_simulator_flask.git

Step 2: Navigate to the project directory.
cd ATM

Step 3: Install the necessary dependencies.
Install Backend Dependencies
cd flask_backend
pip install -r requirements.txt

Install Frontend Dependencies
cd ../frontend
npm install

Step 4: Start the development server for frontend.
npm run dev

Step 5: Start the backend server.
From the flask_backend folder
python run.py
