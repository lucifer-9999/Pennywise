Expense Tracking System

An Expense Tracking System built with FastAPI, Streamlit, and SQLite to manage, analyze, and visualize personal or business expenses.
This project demonstrates a full-stack Python application combining backend APIs, frontend dashboards, and database integration.


You said:

PS C:\Users\ankur\OneDrive\Documents\Desktop\CODE BASICS\project-expense-tracking> Pip freeze | grep streamlit
grep : The term 'grep' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path 
was included, verify that the path is correct and try again.
At line:1 char:14
+ Pip freeze | grep streamlit
+              ~~~~
    + CategoryInfo          : ObjectNotFound: (grep:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\ankur\OneDrive\Documents\Desktop\CODE BASICS\project-expense-tracking> 
ChatGPT said:

You’re on Windows PowerShell, that’s why grep isn’t working (it’s a Linux/macOS command).

Here are the alternatives you can use in PowerShell:

✅ Option 1: Use findstr (Windows equivalent of grep)
pip freeze | findstr streamlit

✅ Option 2: Just search manually with pip
pip show streamlit


This will directly show if streamlit is installed, its version, and the installation path.

✅ Option 3: List all installed packages and look
pip list


👉 If you want to make Linux commands like grep available on Windows, you can install Git Bash or use WSL (Windows Subsystem for Linux).

Do you want me to show you how to check whether streamlit is installed using only PowerShell commands, without installing anything extra?

You said:
i made a project of expense tracking system using fast api , streamlit , json , postman , pycharm etc 
the above ss has files i used 
write a readme,md for me
ChatGPT said:

Got it 👍 Thanks for sharing the screenshot of your project structure. I’ll draft a professional README.md for your Expense Tracking System project.

Here’s a first version you can use and customize further:

💰 Expense Tracking System

An Expense Tracking System built with FastAPI, Streamlit, and SQLite to manage, analyze, and visualize personal or business expenses.
This project demonstrates a full-stack Python application combining backend APIs, frontend dashboards, and database integration.

🚀 Features

Backend (FastAPI)
RESTful API for managing expenses
SQLite database integration
Logging setup for debugging and monitoring

Frontend (Streamlit)
Add and update expenses via a simple UI
Interactive analytics dashboard for expense visualization

Database
SQLite (expenses.db) to persist expense records

Testing
Unit tests with pytest
API Testing
Endpoints tested using Postman and JSON payloads



📂 Project Structure
project-expense-tracking/
│── backend/
│   ├── __init__.py
│   ├── db_helper.py        # Database helper functions
│   ├── logging_setup.py    # Logging configuration
│   ├── server.py           # FastAPI server
│   └── server.log          # Log file
│
│── frontend/
│   ├── add_update_ui.py    # Streamlit UI for adding/updating expenses
│   ├── analytics_ui.py     # Streamlit analytics dashboard
│   └── app.py              # Main Streamlit app
│
│── test/
│   ├── backend/
│   ├── frontend/
│   ├── __init__.py
│   └── conftest.py         # Test configuration
│
│── expenses.db             # SQLite database
│── Readme.md               # Project documentation

