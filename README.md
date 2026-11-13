
# Flask Full CRUD REST API

## Description
A simple Event Management REST API built using Python and Flask.

The API supports creating, viewing, updating, and deleting events.

## Features
- GET: Retrieve all events.
- POST: Create a new event.
- PATCH: Update an event title.
- DELETE: Remove an event.
- JSON responses and HTTP status codes.
- Input validation and error handling.

## API Endpoints

| HTTP Method | Endpoint | Description |
|---|---|---|
| GET | / | Welcome message |
| GET | /events | Retrieve all events |
| POST | /events | Create an event |
| PATCH | /events/<id> | Update an event |
| DELETE | /events/<id> | Delete an event |

## Installation

1. Create a virtual environment:
   python3 -m venv venv

2. Activate the environment:
   source venv/bin/activate

3. Install Flask:
   pip install flask

4. Run the application:
   python app.py

## Example JSON

{
  "title": "Hackathon"
}

## Technologies
- Python
- Flask
- REST API
- JSON
