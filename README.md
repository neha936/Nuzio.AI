# Nuzio.AI

Nuzio.AI is a personalized news and audio platform that allows users to securely log in, access personalized news content, and listen to news through an interactive audio player.

## Live Demo

https://nuzio-ai-sigma.vercel.app/

## Features

- JWT-based user authentication
- Secure login and logout
- Protected routes
- Personalized news feed
- Audio news playback
- Interactive Now Playing interface
- Play/Pause controls
- Previous/Next navigation
- Responsive user interface
- REST API integration
- Input validation and error handling

## Tech Stack

- React.js
- Vite
- JavaScript
- CSS
- Node.js
- Express.js
- JWT Authentication
- REST APIs

## Application Flow

Login → JWT Authentication → Personalized News → Select News → Now Playing → Audio Playback

## API Endpoint

### Login

POST /api/auth/login

Authenticates the user and returns a JWT token.

### Protected APIs

Protected endpoints require a valid JWT token in the request header:

Authorization: Bearer <JWT_TOKEN>

## Environment Variables

Create a `.env` file in the backend and configure the required environment variables.

PORT=5000
JWT_SECRET=your_jwt_secret

Add any additional API keys or configuration required by the application.

> Never commit `.env` files or API keys to the repository.

## Installation

### Clone the Repository

git clone https://github.com/neha936/Nuzio.AI.git
cd Nuzio.AI

### Frontend Setup

cd Frontend
npm install
npm run dev

### Backend Setup

cd Backend
npm install
npm start

Make sure the required environment variables are configured before starting the backend.

## Deployment

Frontend: Vercel

Backend: Render

## Live Application

https://nuzio-ai-sigma.vercel.app/
