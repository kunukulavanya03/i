# i

Backend API for i

## Tech Stack

- **Frontend**: React
- **Backend**: FastAPI + SQLAlchemy
- **Frontend Source**: GitHub ([Repository](https://github.com/HimaShankarReddyEguturi/Designecommerceproductui.git))

## Project Structure

```
i/
├── frontend/          # Frontend application
├── backend/           # Backend API
├── README.md          # This file
└── docker-compose.yml # Docker configuration (if applicable)
```

## Getting Started

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.11+ (for Python backends)
- Docker (optional, for containerized setup)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
# Follow backend-specific setup instructions in backend/README.md
```

## Features

- user profiles
- friend requests
- search

## API Endpoints

- `POST /api/register` - Create a new user account
- `POST /api/login` - Log in to an existing user account
- `GET /api/profile` - View the current user's profile
- `PUT /api/profile` - Edit the current user's profile
- `GET /api/users` - View a list of all users
- `GET /api/users/search` - Search for users by username or email
- `POST /api/friend-requests` - Send a friend request to another user
- `PUT /api/friend-requests/{id}` - Accept or decline a friend request

## License

MIT
