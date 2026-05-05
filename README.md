# SpringBoot FSAD Project

A full-stack application with Spring Boot backend, Python gateway, and React frontend.

## Project Structure

```
├── backend/
│   ├── coreservices/       # Spring Boot microservice
│   └── gateway/            # Python API Gateway
└── frontend/               # React/Vite frontend
```

## Tech Stack

- **Backend**: Spring Boot, Java, Maven
- **Gateway**: Python (Flask/FastAPI)
- **Frontend**: React, Vite, JavaScript

## Getting Started

### Backend Services

Navigate to `backend/coreservices/`:
```bash
cd backend/coreservices
mvn spring-boot:run
```

### Gateway

Navigate to `backend/gateway/`:
```bash
pip install -r requirements.txt
python run.py
```

### Frontend

Navigate to `frontend/`:
```bash
npm install
npm run dev
```

## Project Features

- User authentication and JWT tokens
- Role-based access control
- Menu management
- Task management
- User profile management

## License

MIT
