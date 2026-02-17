# Mergington High School Activities

A FastAPI web application that allows students to view and sign up for extracurricular activities at Mergington High School, with teacher-managed registration.

## Features

### For Students
- **Browse Activities**: View all available extracurricular activities across multiple categories (Sports, Arts, Academic, Community, Technology)
- **Advanced Filtering**: Filter activities by category, day of the week, and time of day (before school, after school, weekend)
- **Search**: Quickly find activities using the search functionality
- **Activity Details**: View comprehensive information including description, schedule, and current participant count

### For Teachers
- **Authentication**: Secure login system for teachers
- **Student Registration**: Register students for activities with teacher authorization
- **Student Unregistration**: Remove students from activities as needed
- **Activity Management**: Access to all activity operations

## Technology Stack

- **Backend**: FastAPI (Python)
- **Database**: MongoDB with pymongo
- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Authentication**: Argon2 password hashing

## Application Structure

- `app.py` - Main FastAPI application entry point
- `backend/` - Backend API implementation
  - `routers/` - API route handlers for activities and authentication
  - `database.py` - MongoDB database configuration and initialization
- `static/` - Frontend files (HTML, CSS, JavaScript)

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).
