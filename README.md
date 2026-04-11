# CrimeFiles — Detective Simulator

An interactive crime investigation simulator where users solve fictional cases by analyzing clues, connecting evidence, and making deductions.

## Live Demo

🌐 [Try the Project](https://clue-connect-crime-simulator.vercel.app)

## Overview

CrimeFiles is a detective-style simulator built for hackathons and interactive learning experiences. Players investigate crime scenes, review evidence, connect clues, and progress through mystery cases in an engaging interface.

The project focuses on creating an immersive experience using modern frontend technologies, animations, and drag-and-drop interactions.

The repository is built with a fast React + Vite setup and uses Supabase for backend-related functionality. :contentReference[oaicite:0]{index=0}

## Features

- Interactive detective gameplay
- Crime case investigation flow
- Evidence and clue analysis
- Drag-and-drop clue management
- Smooth animations and transitions
- Responsive design for desktop and mobile
- State management with Zustand
- Backend integration with Supabase
- Clean and modern UI built with Tailwind CSS

## Tech Stack

### Frontend
- React
- Vite
- Tailwind CSS
- Framer Motion
- Lucide React Icons

### State Management
- Zustand

### Backend / Database
- Supabase

### Other Libraries
- @hello-pangea/dnd for drag-and-drop functionality

The project uses React, Vite, Tailwind CSS, Zustand, Supabase, Framer Motion, and drag-and-drop support through `@hello-pangea/dnd`. :contentReference[oaicite:1]{index=1}

## Folder Structure

```bash
CrimeFiles/
├── public/
├── src/
├── .env.example
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md

## Installation

1. Clone the repository

```bash
git clone https://github.com/parthbadgire-code/ClueConnect-CrimeSimulator.git
```

2. Navigate to the project directory

```bash
cd ClueConnect-CrimeSimulator
```

3. Install dependencies

```bash
npm install
```

4. Create an environment file

```bash
cp .env.example .env
```

5. Add your Supabase credentials to the `.env` file

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

6. Start the development server

```bash
npm run dev
```

7. Open the app in your browser

```text
http://localhost:5173
```

## Available Scripts

```bash
npm run dev       # Start development server
npm run build     # Build for production
npm run preview   # Preview production build locally
npm run lint      # Run ESLint
```

## Build for Production

To create a production build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## Environment Variables

Create a `.env` file in the root directory and add:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Future Improvements

- Multiple crime cases
- Difficulty levels
- Save game progress
- User authentication
- Leaderboards
- Multiplayer detective mode
- AI-generated crime stories
- Achievement system

## Contributing

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/your-feature-name
```

3. Make your changes
4. Commit your changes

```bash
git commit -m "Add your feature"
```

5. Push the branch

```bash
git push origin feature/your-feature-name
```

6. Open a Pull Request

## License

This project is licensed under the MIT License.

## Author

Built by Parth Badgire and contributors.
