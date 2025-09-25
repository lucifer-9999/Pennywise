

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

