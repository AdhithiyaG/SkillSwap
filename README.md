# Skill Exchange Platform

[![Node.js](https://img.shields.io/badge/Node.js-Express-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-Vite-61DAFB?logo=react&logoColor=0A0A0A)](https://react.dev/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Auth](https://img.shields.io/badge/Auth-JWT-000000?logo=jsonwebtokens&logoColor=white)](https://jwt.io/)

A full-stack platform where users exchange skills, discover good matches, send requests, schedule sessions, and leave reviews.

## What it does

- User registration and login with JWT auth
- Skill-based matching between users
- Exchange request workflow (send, accept, manage)
- Session tracking and review system
- Responsive React UI connected to a real API

## Tech Stack

| Layer | Tools |
| --- | --- |
| Frontend | React, Vite, Tailwind CSS, Axios |
| Backend | Node.js, Express, Mongoose |
| Database | MongoDB |
| Auth | JWT |

## Quick Start

### 1) Backend

```bash
cd backend
npm install
npm run dev
```

### 2) Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on Vite dev server and calls backend API endpoints.

## Project Structure

```text
backend/
  controllers/  models/  routes/  middleware/
frontend/
  src/components/  src/pages/  src/context/
```

## Core Pages

- Login / Register
- Matches
- Requests
- Sessions
- Profile

## Status

Active development project for skill-sharing workflows.
