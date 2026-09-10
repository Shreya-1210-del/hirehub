# HireHub

A full-stack job recruitment platform built with React and Django REST Framework.

HireHub is designed to connect candidates with job opportunities through a modern web interface and a REST-based backend. The application demonstrates full-stack development using React on the frontend and Django REST Framework on the backend.

---

## Overview

HireHub follows a client-server architecture where the React frontend communicates with a Django REST API.

The frontend is responsible for the user interface, navigation, user interactions, and communication with the backend.

The backend handles authentication, application logic, job-related data, database operations, and REST API responses.

The project is being developed as a practical full-stack software engineering project with an emphasis on clean architecture, reusable components, REST APIs, database interaction, and authentication.

---

## Features

- User registration
- User authentication
- User login
- Job listings
- Job details
- Job application functionality
- Duplicate application prevention
- User-related API functionality
- RESTful backend APIs
- React Router navigation
- Responsive user interface
- Tailwind CSS styling
- PostgreSQL database support
- SQLite support for development
- API testing with Postman

---

## Tech Stack

### Frontend

- React
- Vite
- JavaScript
- Tailwind CSS
- React Router

### Backend

- Python
- Django
- Django REST Framework

### Database

- PostgreSQL
- SQLite

### Tools

- Git
- GitHub
- Postman
- VS Code
- npm

---

## Architecture

HireHub uses a separated frontend and backend architecture.

```text
                    HireHub
                       |
          +------------+------------+
          |                         |
          v                         v
   React Frontend            Django Backend
          |                         |
          |      HTTP Requests      |
          +-------------------------+
                                    |
                                    v
                           Django REST API
                                    |
                                    v
                                Database
