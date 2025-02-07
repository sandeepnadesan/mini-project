# Project Management App Documentation

## Overview
The Project Management App is a web-based application designed to help teams collaborate efficiently, track tasks, and manage projects seamlessly. It provides an intuitive interface with essential features for project planning, task assignment, and progress monitoring.

## Objective
The objective of this application is to provide teams with a comprehensive tool to manage projects effectively, ensure transparency in task management, and enhance productivity through collaboration features and real-time progress tracking.

## Workflow
1. **User Registration/Login**: Users authenticate securely to access the platform.
2. **Project Creation**: Users create projects and define goals.
3. **Task Assignment**: Tasks are assigned to team members with priorities and deadlines.
4. **Collaboration**: Users communicate through comments and file sharing.
5. **Tracking Progress**: Progress is monitored via dashboards and reports.
6. **Notifications**: Users receive alerts for updates and deadlines.
7. **Completion & Review**: Project status is reviewed and marked as complete.

## Technology Stack
- **Frontend**: React.js
- **Backend**: Django (Python)
- **Database**: MongoDB
- **Authentication**: JWT-based authentication
- **Deployment**: Docker, AWS

## Features
- **User Authentication**: Secure login and registration for users.
- **Project Creation**: Users can create and manage multiple projects.
- **Task Management**: Assign tasks to team members with due dates and priorities.
- **Progress Tracking**: View project progress through dashboards and reports.
- **Collaboration**: Commenting and file sharing within projects.
- **Notifications**: Email and in-app notifications for updates.

## Installation
### Prerequisites
Ensure you have the following installed on your system:
- Node.js
- Python 3.x
- MongoDB
- Docker (optional)

## API Endpoints
| Endpoint           | Method | Description                 |
|-------------------|--------|-----------------------------|
| `/api/auth/login` | POST   | User login                  |
| `/api/auth/signup`| POST   | User registration           |
| `/api/projects`   | GET    | Get all projects            |
| `/api/tasks`      | GET    | Get all tasks               |
| `/api/tasks`      | POST   | Create a new task           |

