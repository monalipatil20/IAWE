# Project Overview

**Title:** Intelligent Autonomous Workflow Engine (IAWE)

**Goal:** Automate task assignment & workflow decisions using intelligent logic

**Users:** Admin + Employees

## Tech Stack

- Frontend: React + Tailwind CSS
- Backend: Node.js + Express
- Database: MongoDB
- Auth: JWT

## Development Timeline

### Week 1: Planning & Setup (Strict)

- Finalize feature list
- Create UI wireframe (rough design)
- Setup project:
  - React app
  - Node backend
  - MongoDB connection

## Week 1 Implementation Status

- Feature baseline drafted in frontend wireframe and backend auth flow stubs
- Rough wireframe implemented in frontend dashboard layout
- React app initialized with Tailwind CSS
- Node.js + Express backend initialized
- MongoDB connection bootstrap added via Mongoose

## Run Instructions

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Backend

```bash
cd backend
copy .env.example .env
npm install
npm run dev
```

### API Health Check

- URL: `http://localhost:5000/api/health`
