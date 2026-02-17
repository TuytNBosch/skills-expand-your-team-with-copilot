# Mergington High School Activities

A web application that allows students to view extracurricular activities and teachers to manage student registrations.

## Features

### For Students
- **Browse Activities**: View all available extracurricular activities with detailed information including schedules, descriptions, and participant counts
- **Search**: Search for specific activities by name or description
- **Filter Activities**: Filter activities by:
  - Category (Sports, Arts, Academic, Community, Technology)
  - Day of the week (Monday through Sunday)
  - Time of day (Before School, After School, Weekend)
- **View Schedules**: See when activities meet, including specific days and times
- **Check Availability**: See how many students are registered and the maximum capacity

### For Teachers
- **Login System**: Secure authentication for teachers to manage registrations
- **Register Students**: Sign up students for activities using their school email
- **Unregister Students**: Remove students from activities when needed
- **View Participants**: See who is registered for each activity

### Additional Features
- **Dark Mode**: Toggle between light and dark themes for comfortable viewing
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Updates**: Activity information updates dynamically

## Technology Stack

- **Backend**: Python with FastAPI
- **Database**: MongoDB
- **Frontend**: HTML, CSS, and JavaScript
- **Authentication**: Teacher login system with password hashing

## Activity Categories

The system supports activities in five categories:
- **Sports**: Soccer Team, Basketball Team, Morning Fitness
- **Arts**: Art Club, Drama Club
- **Academic**: Math Club, Chess Club, Debate Team, Science Olympiad
- **Community**: Various community service activities
- **Technology**: Programming Class, Weekend Robotics Workshop

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).
