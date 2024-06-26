# MadeLine Chatbot

## Description

This project is a FastAPI-based web application. It is designed to provide a secure conversation platform for registered users. The main functionality of this version is to authenticate the user and return a static conversation message.

## Sample Video


https://github.com/rajprem4214/Madeline-Chatbot/assets/85401522/7054bb0d-1eff-4e1d-87de-49c372fb296e




## Setup

This project uses FastAPI and SQLAlchemy, and it requires Python 3.7+.

To start the application, navigate to the project folder and execute the command:

Clone the repository

Run the command `pip install -r requirements.txt`

Run
python main.py

The application will be available at `http://localhost:5555`.

Visit `http://localhost:5555/docs` for testing API endpoints.

## Technologies Used
1. FastAPI 
2. PostgreSQL
3. AsyncIO
4. Pydantic
5. OpenAI/Or Gemini
6. Langchain

## Key Features

- User registration and authentication system with OAuth2.
- Secure conversation endpoint that returns a static message and the authenticated user's username.
- SQLite database for user data persistence.

## Environment Variables

To run this project, you will need to add the following environment variable:

- `SECRET_KEY`: Your secret key for encoding and decoding the JWT tokens.

Please use a `.env` file for setting this environment variable. The `.env` file is ignored by git to ensure sensitive items are not accidentally published.
