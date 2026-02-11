💼 Pro Job Portal Backend

This is a professional, production-ready Job Portal Backend built with FastAPI. It features secure authentication, data validation, and complex database relationships.

🚀 Key Features

JWT Authentication: Secure user sessions using JSON Web Tokens.

Password Hashing: Industry-standard security using bcrypt.

Relational Database: Complex relationships between Users and Jobs using SQLAlchemy ORM.

Data Validation: Strict input/output handling with Pydantic.

Interactive API Docs: Built-in Swagger UI for testing.

🛠️ Tech Stack

Backend: FastAPI (Python)

Database: SQLite (SQLAlchemy ORM)

Security: Passlib, Python-JOSE, Bcrypt

Environment: Modular Python Architecture

📂 Project Structure

app/
├── main.py          # Entry point & Endpoints
├── database.py      # DB Connection Logic
├── models.py        # SQLAlchemy Tables (User, Job)
├── schemas.py       # Pydantic Schemas
└── auth_utils.py    # JWT & Password Security


⚙️ Setup & Run

Clone the repo:
git clone https://github.com/Omkar1549/job-portal-backend.git

Install dependencies:
pip install fastapi uvicorn sqlalchemy passlib[bcrypt] python-jose[cryptography]

Run Server:
python -m uvicorn main:app --reload

Built by Omkar Kandekar during the 21-Day Job Mastery Challenge. 🚀
