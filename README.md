# Google Drive Clone

A full-stack cloud storage application inspired by Google Drive, built to provide secure file management and user authentication through a modern web interface.

## Features

- User registration and login
- JWT-based authentication
- Password hashing with bcrypt
- File and folder management
- Cloud storage integration
- User-specific storage
- Protected API routes
- API rate limiting
- Security headers with Helmet
- CORS configuration
- API request logging
- Docker and Docker Compose support
- React and Vite frontend

## Tech Stack

### Frontend
- React
- Vite
- JavaScript
- CSS

### Backend
- Node.js
- Express.js
- REST APIs
- JWT
- bcrypt

### Database and Storage
- Supabase

### Security and DevOps
- Helmet
- CORS
- Express Rate Limit
- Morgan
- Docker

## Project Structure

```text
Google-Drive-Clone/
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── routes/
│   ├── config/
│   └── server.js
│
├── frontend/
│   ├── src/
│   └── public/
│
├── docker-compose.yml
└── README.md
```

## Authentication

The application uses JWT-based authentication to secure user-specific resources.

Passwords are securely hashed using bcrypt before being stored, while protected API endpoints require a valid authentication token.

## Project Objective

The goal of this project is to understand and implement the core concepts behind a cloud storage platform, including authentication, REST API development, database integration, file management, security, and frontend-backend communication.

## Future Improvements

- Real-time file upload and download
- Folder creation and organization
- File sharing
- File preview
- Search and filtering
- Storage usage dashboard
- Trash/recycle-bin functionality
- File versioning
- Public and private sharing links

## Author

**Jorin Nayak**

Built as a full-stack development project to explore modern web development, backend architecture, authentication, and cloud storage.
