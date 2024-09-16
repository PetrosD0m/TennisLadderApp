# TennisLadderApp
The application manages a list of players with the ability to challenge and record match results. It also includes the capability to view match history, player rankings, and handle player registration and deletion requests.
Developed a Tennis Ladder application using Python, Flask framework for the web server, and SQLite database for storing and managing player data, matches, and rankings. The application allows users to register new players, challenge opponents, record match results, and manage rankings.

Technologies:

Python
Flask framework for web application development
SQLite for data storage
HTML for dynamic web pages using Flask
Tkinter for creating a graphical user interface (GUI)

Tennis Ladder Application Installation Guide

System Requirements
Before starting the installation, ensure you have Python installed on your system. You can download Python from the official Python website. The system requirements are:

Python 3.x installed on your system.
Internet connection for downloading the required libraries.
Installation Steps
Download and Install Python:

Download the latest version of Python from the official Python website.
Follow the installation instructions for your operating system.
Ensure that you select the option "Add Python to PATH" during installation.
Create and activate a virtual environment (optional but recommended):

bash
python -m venv venv
source venv/bin/activate
# On Windows: 
venv\Scripts\activate
Create a folder for the application:

Create a new folder on your computer to store the application files, e.g., C:\TennisLadder.
Download the application files:

Copy the application code and save it into a file named tennis_ladder.py inside the folder you created in the previous step.
You can use PyCharm Community Edition to run the application code.
Install required libraries:

Open Command Prompt (or Terminal on macOS/Linux).
Install the required libraries by running the following command:
pip install flask
Note: The libraries sqlite3, random, string, webbrowser, threading, and tkinter are built into Python and do not require separate installation.

Create the database:

Run the tennis_ladder.py file to create the necessary tables in the database.
The application will automatically create the tennis_ladder.db database in the same folder as the code file. If it already exists, it will be used.
Running the Program:
Open Command Prompt (or Terminal) and navigate to the folder where you saved the code file:

bash
cd C:\TennisLadder
# Or on macOS/Linux:
cd /Users/username/TennisLadder
Run the program with the following command:


python tennis_ladder.py
Alternatively, you can use PyCharm to run the application code.

Using the Application:
Execute the tennis_ladder.py file to start the application.
Follow the instructions in the application's graphical interface to register, delete players, challenge matches, and record results.
Application Features:
Register Player: Allows submitting a request to register a new player.
Delete Player: Allows submitting a request to delete a player.
Admin Login: Allows admin login to process registration, deletion, and challenge requests.
View Ladder: Displays the current player rankings.
View Match History: Displays the history of previous matches.
Challenge Player: Allows submitting a challenge to other players.
Record Match Result: Allows submitting a request to record a match result for admin approval.
View Challenges: Displays the current challenges between players.
View Rules: Locally serves the page with the rules and history in the default web browser.
Flask Server Details:
The application includes a Flask server that serves a local page with the rules. To ensure the server works correctly:

Start Flask Server: The application automatically starts the Flask server in a separate thread when you run tennis_ladder.py. You don’t need to do anything additional for this.
Access the Rules Page: The rules page is available at the address http://127.0.0.1:5000/rules.
Notes:
Ensure you have admin privileges to process registration, deletion, and challenge requests. The admin login password is: admin.
When running the application, open the local Flask server to view the rules and match history in your web browser.
The application runs locally and does not require an internet connection after the initial library installation.
