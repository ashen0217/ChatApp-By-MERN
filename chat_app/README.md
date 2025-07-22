# ChatApp-By-MERN

A real-time chat application built using the MERN (MongoDB, Express.js, React, Node.js) stack.

## Project Structure

```
chat_app/
├── backend/              # Backend Node.js/Express server
│   └── server.js        # Express server setup
├── frontend/            # React frontend (Vite)
│   ├── public/         # Static assets
│   ├── src/            # Source code
│   │   ├── assets/     # Frontend assets
│   │   ├── App.jsx     # Main React component
│   │   └── main.jsx    # Application entry point
│   ├── index.html      # HTML entry point
│   └── vite.config.js  # Vite configuration
```

## Tech Stack

### Frontend

- React 18
- Vite 6
- ESLint for code quality
- Modern JavaScript (ES6+)

### Backend

- Node.js
- Express.js
- Running on port 5000

## Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/ashen0217/ChatApp-By-MERN.git
```

2. Install Frontend Dependencies:

```bash
cd chat_app/frontend
npm install
```

3. Install Backend Dependencies:

```bash
cd ../backend
npm install
```

### Running the Application

1. Start the Backend Server:

```bash
cd backend
npm start
```

2. Start the Frontend Development Server:

```bash
cd frontend
npm run dev
```

## Development

- Frontend development server runs with hot reload enabled
- Backend API server runs on port 5000
- ESLint is configured for code quality

## Scripts

### Frontend

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
