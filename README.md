# Remind Me Later – API (Django)

This is a backend API built for the Symplique Solutions internship task.

## 📝 Task

Create an API that accepts and stores:
- Date
- Time
- Message

The data is saved in a database. No reminder delivery logic is required.

## 🔧 Tech Stack

- Python
- Django
- Django REST Framework
- SQLite (default DB)

## 🚀 How to Run

1. Clone the repo  
2. Install dependencies: pip install -r requirements.txt
3. Run migrations: python manage.py migrate
4. Start the server: python manage.py runserver
5. Test the endpoint: POST http://127.0.0.1:8000/api/reminders/
example JSON:
{
  "date": "2025-06-01",
  "time": "14:30:00",
  "message": "Team meeting"
}
