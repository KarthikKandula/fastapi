# fastapi
Learn/Practice FastAPI

## Sample folder structure
```
/project-root
├── app/
│   ├── api/
│   │   └── v1/
│   │       ├── __init__.py
│   │       ├── users.py           # User endpoints (using APIRouter)
│   │       └── items.py           # Item endpoints (using APIRouter)
│   ├── core/
│   │   ├── __init__.py
│   │   ├── config.py            # Global configuration (Pydantic BaseSettings)
│   │   └── security.py          # Security helpers
│   ├── database/
│   │   ├── __init__.py
│   │   ├── session.py           # Database session management
│   │   └── base.py              # Declarative base for models
│   ├── models/
│   │   ├── __init__.py
│   │   └── user.py              # SQLAlchemy models (database tables)
│   ├── schemas/
│   │   ├── __init__.py
│   │   └── user.py              # Pydantic models (data validation/serialization)
│   ├── services/
│   │   ├── __init__.py
│   │   └── user_service.py      # Business logic (separated from routes)
│   ├── main.py                # Main application entry point (includes routers)
│   └── __init__.py            # Marks 'app' as a Python package
├── tests/
│   ├── __init__.py
│   └── test_app.py              # Test cases
├── requirements.txt           # Project dependencies
├── .env                       # Environment variables
└── Dockerfile                 # (Optional) Docker configuration
```
