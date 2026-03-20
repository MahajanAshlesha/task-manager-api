# Task Manager API

A RESTful Task Manager API built with Python and FastAPI, featuring full CRUD operations and persistent SQLite database storage.

## Tech Stack
- Python 3.13
- FastAPI
- SQLAlchemy
- SQLite
- Uvicorn

## Installation

1. Clone the repository
```
git clone https://github.com/ashleshamahajan/task-manager-api
```

2. Create virtual environment
```
python3 -m venv venv
source venv/bin/activate
```

3. Install dependencies
```
pip install -r requirements.txt
```

4. Run the server
```
python3 -m uvicorn main:app --reload
```

5. Open docs
```
http://127.0.0.1:8000/docs
```

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | / | Home |
| POST | /tasks | Create a task |
| GET | /tasks | Get all tasks |
| PUT | /tasks/{id} | Update a task |
| DELETE | /tasks/{id} | Delete a task |

## Author
Ashlesha Mahajan
