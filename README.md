# ScaleX Innovation Internship

This repository contains my learning progress, projects, implementation phases, and weekly reports completed during my Software Development Internship at ScaleX Innovation.

## Internship Objectives

The internship focuses on developing full-stack AI-powered applications using:

- Flutter
- Django
- Django REST Framework (DRF)
- Groq API
- Llama 3.1
- LangGraph

---

## Repository Structure

```text
.
├── reports/
│   ├── week-01-report.md
│   └── week-02-report.md
├── screenshots/
├── README.md
└── mysite/
    ├── manage.py
    ├── mysite/
    └── polls/
```

---

## Progress

### Week 1

#### Flutter Learning Path

- Completed the Flutter Learning Pathway (17/17 modules)
- Built the Wikipedia Reader application
- Studied Flutter widgets and UI design
- Learned state management using ChangeNotifier and ListenableBuilder
- Practiced API integration and JSON parsing
- Implemented responsive and adaptive layouts
- Learned Flutter navigation and routing

#### Django Fundamentals

- Installed and configured Django 6.0.6
- Created Django projects and applications
- Learned URL routing and views
- Implemented database models
- Performed migrations
- Configured and used Django Admin
- Learned Django project structure and best practices

---

### Week 2

#### Backend Development with Django REST Framework

Implemented the following API endpoints:

- Hello API (`/hello/`)
- User Registration API (`/register/`)
- User Login API (`/login/`)
- Chat API (`/chat/`)

Features completed:

- User registration and authentication
- JSON request and response handling
- API testing using Django REST Framework Browsable API
- SQLite database integration
- Backend architecture for AI-powered chat functionality

---

#### AI Integration

Integrated Groq API with the Llama 3.1 model.

Features completed:

- Groq API configuration
- Llama 3.1 model integration
- AI-powered response generation
- Prompt processing and response handling
- Backend-to-AI communication
- API testing and validation

---

#### Flutter Frontend Integration

Built a Flutter Web interface connected to the Django backend.

Features completed:

- Chat interface
- User input handling
- HTTP communication with Django backend
- JSON request/response processing
- Real-time response display
- Frontend-backend integration testing

---

#### LangGraph Agentic Workflow

Implemented a LangGraph-based multi-agent workflow.

Architecture:

```text
User Message
      │
      ▼
 Router Agent
   /       \
  ▼         ▼
Coding    General
 Agent      Agent
      \    /
       ▼  ▼
     Response
```

Components:

- Router Agent
- Coding Agent
- General Agent
- Conditional Routing
- StateGraph Workflow

Features completed:

- LangGraph installation and configuration
- StateGraph workflow implementation
- Query classification and routing
- Multi-agent orchestration
- Integration with Django Chat API
- End-to-end workflow testing

---

## System Architecture

```text
Flutter Web
      │
      ▼
Django REST Framework
      │
      ▼
LangGraph Workflow
      │
      ▼
Router Agent
   ├── Coding Agent
   └── General Agent
      │
      ▼
Groq API (Llama 3.1)
```

---

## Project Status


### Phase 1 – Flutter Learning Path
✅ Completed

- Flutter fundamentals mastered
- Wikipedia Reader project completed
- State management and API integration practiced

### Phase 2 – Django Backend Development
✅ Completed

- Django REST Framework configured
- Authentication system implemented
- API endpoints developed and tested

### Phase 3 – AI Integration
✅ Completed

- Groq API integrated
- Llama 3.1 model connected
- AI chat responses operational
- Flutter frontend connected successfully

### Phase 4 – LangGraph Agentic Workflow
✅ Completed

- StateGraph workflow implemented
- Router Agent operational
- Coding Agent operational
- General Agent operational
- Conditional routing implemented
- Django integration verified
- API testing completed successfully

---

## Weekly Reports

- [Week 1 Report](reports/week-01-report.md)
- [Week 2 Report](reports/week-02-report.md)

---

## Technologies Used

| Category | Technology |
|-----------|------------|
| Frontend | Flutter Web |
| Backend | Django 6.0.6 |
| API Framework | Django REST Framework |
| Programming Language | Python |
| Programming Language | Dart |
| Database | SQLite |
| AI Service | Groq API |
| AI Model | Llama 3.1 |
| Agent Framework | LangGraph |
| CORS Middleware | django-cors-headers |

---

## Screenshots

The `screenshots/` directory contains visual documentation of:

- Flutter frontend development
- Django REST Framework APIs
- User authentication
- Chat API implementation
- Groq API integration
- AI response generation
- Database verification
- LangGraph workflow implementation
- End-to-end system testing

---

## Future Improvements

- Chat history persistence
- JWT authentication
- User profile management
- Advanced CRUD operations
- Improved UI/UX
- Production deployment
- Monitoring and analytics
- Additional specialized AI agents

---

**Intern:** Alaa Elmir  
**Organization:** ScaleX Innovation  
**Role:** Software Development Intern
