# Collaborative Code Editor

A real-time collaborative code editor built with the MERN stack, featuring Monaco Editor and Yjs for synchronization.

## Features

- Real-time collaborative editing
- Monaco Editor integration
- User presence indicators
- Responsive UI with Tailwind CSS

## Tech Stack

- **Frontend:** React, Vite, Monaco Editor, Yjs, Tailwind CSS
- **Backend:** Node.js, Express, Socket.IO, Y-Socket.IO
- **Containerization:** Docker

## Prerequisites

- Node.js (v20 or higher)
- Docker (optional, for containerized deployment)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MDSONU22943/DOCKER-AWS.git
   cd DOCKER-AWS
   ```

2. Install backend dependencies:
   ```bash
   cd Backend
   npm install
   ```

3. Install frontend dependencies:
   ```bash
   cd ../Frontend
   npm install
   ```

## Running Locally

1. Start the backend server:
   ```bash
   cd Backend
   npm run dev
   ```

2. In a new terminal, start the frontend:
   ```bash
   cd Frontend
   npm run dev
   ```

3. Open your browser to `http://localhost:5173` (Vite default port)

## Docker Setup

To run the backend in a Docker container:

1. Build the Docker image:
   ```bash
   docker build -t collaborative-editor-backend .
   ```

2. Run the container:
   ```bash
   docker run -p 3000:3000 collaborative-editor-backend
   ```

Note: Frontend needs to be run separately or served statically.

## Usage

1. Enter a username to join the editor.
2. Start typing in the Monaco editor.
3. See real-time updates from other users.
4. View connected users in the sidebar.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

ISC License