# React Firebase Project

A modern web application built with React and Firebase, featuring real-time data synchronization and cloud deployment capabilities.

## Tech Stack

- **React** - Frontend library for building user interfaces
- **Firebase** - Backend-as-a-Service for authentication, database, and hosting
- **Vite** - Fast build tool and development server
- **TypeScript** - Type-safe JavaScript
- **SASS** - CSS preprocessor for enhanced styling

## Features

- Firebase Authentication integration
- Real-time database with Firestore
- Firebase Hosting for deployment
- Modern React with Hooks
- TypeScript for type safety
- Fast development with Vite HMR

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn
- Firebase CLI (`npm install -g firebase-tools`)

## Getting Started

### Installation

1. Clone the repository
```bash
git clone https://github.com/Achuabhal/react-firebase.git
cd react-firebase
```

2. Navigate to the project directory
```bash
cd my-app
```

3. Install dependencies
```bash
npm install
```

4. Set up Firebase configuration
   - Create a `.env` file in the `my-app` directory
   - Add your Firebase configuration:
```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### Development

Run the development server:
```bash
npm run dev
```

The app will be available at `http://localhost:5173`

### Build

Create a production build:
```bash
npm run build
```

### Deploy to Firebase

1. Login to Firebase:
```bash
firebase login
```

2. Deploy to Firebase Hosting:
```bash
npm run build
firebase deploy
```

## Project Structure

```
react-firebase/
├── my-app/
│   ├── src/              # Source files
│   ├── public/           # Static assets
│   ├── .env             # Environment variables
│   ├── firebase.json    # Firebase configuration
│   ├── vite.config.ts   # Vite configuration
│   └── package.json     # Project dependencies
└── README.md
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Firebase Services Used

- **Authentication** - User authentication and authorization
- **Firestore** - NoSQL cloud database
- **Hosting** - Web app hosting

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

[Achuabhal](https://github.com/Achuabhal)
