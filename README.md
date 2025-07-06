ChessForge ♔
ChessForge is an open-source chess platform that brings the classic game of chess to the modern web. Built with performance, accessibility, and user experience in mind, ChessForge offers everything you need to play, learn, and improve your chess game.

✨ Features
Core Gameplay
Real-time multiplayer chess with WebSocket connections
Play against AI with multiple difficulty levels
Local hotseat mode for playing with friends on the same device
Chess variants including King of the Hill, Three-Check, and Atomic Chess
Time controls supporting bullet, blitz, rapid, and classical formats
Learning & Analysis
Interactive chess lessons for players of all skill levels
Puzzle trainer with thousands of tactical puzzles
Game analysis with computer evaluation and move suggestions
Opening explorer with extensive opening database
Endgame trainer for practicing crucial endgame positions

Community Features
User profiles with rating tracking and game history
Friend system with private messaging
Tournaments with Swiss and round-robin formats
Chess clubs for organizing team matches and events
Spectator mode for watching live games
Modern Interface
Responsive design that works on desktop, tablet, and mobile
Customizable board themes and piece sets
Dark/light mode support
Accessibility features including screen reader support
Multiple language support

🚀 Getting Started
Prerequisites
Node.js 18+ and npm
PostgreSQL 13+


# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your database and Redis configurations

# Run database migrations
npm run migrate

# Start the development server
npm run dev
Visit http://localhost:3000 to see ChessForge in action!

🛠️ Tech Stack
Frontend
React 18 with TypeScript
Next.js 14 for server-side rendering
Tailwind CSS for styling
Framer Motion for animations
Socket.io Client for real-time communication
Backend
Node.js with Express
TypeScript for type safety
Socket.io for WebSocket handling
PostgreSQL with Prisma ORM
Redis for session management and caching
JWT for authentication
Chess Engine
Stockfish integration for AI opponents and analysis
chess.js for move validation and game logic
Custom evaluation for position assessment
📁 Project Structure
chessforge/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Next.js pages
│   │   ├── hooks/         # Custom React hooks
│   │   ├── utils/         # Utility functions
│   │   └── types/         # TypeScript type definitions
├── server/                # Node.js backend
│   ├── src/
│   │   ├── controllers/   # Route handlers
│   │   ├── middleware/    # Express middleware
│   │   ├── models/        # Database models
│   │   ├── services/      # Business logic
│   │   └── socket/        # Socket.io handlers
├── shared/                # Shared types and utilities
├── database/              # Database migrations and seeds
└── docs/                  # Documentation
🎮 How to Play
Create an account or play as a guest
Choose your game mode: Quick match, custom game, or AI opponent
Select time controls that suit your playing style
Make your moves by clicking and dragging pieces
Analyze your games after completion to improve your play
🤝 Contributing
We welcome contributions from chess enthusiasts and developers of all skill levels!

How to Contribute
Fork the repository
Create a feature branch: git checkout -b feature/amazing-feature
Make your changes and add tests if applicable
Commit your changes: git commit -m 'Add amazing feature'
Push to the branch: git push origin feature/amazing-feature
Open a Pull Request
Development Guidelines
Follow the existing code style and conventions
Write clear commit messages
Add tests for new features
Update documentation as needed
Ensure your code passes all linting and tests
Areas for Contribution
🐛 Bug fixes and performance improvements
🎨 UI/UX enhancements and new themes
🧩 New chess variants and game modes
🎓 Educational content and tutorials
🌍 Internationalization and translations
📱 Mobile app development (React Native)
📊 Roadmap
Version 1.0 (Current)
 Basic chess gameplay
 User authentication
 Real-time multiplayer
 AI opponents
Version 1.1 (Next)
 Tournament system
 Advanced analysis tools
 Mobile app beta
 Chess variants
Version 2.0 (Future)
 Video chat during games
 Streaming integration
 Advanced AI training
 VR chess experience
🏆 Community
Discord: Join our community server for discussions and support
Reddit: Follow r/ChessForge for updates and community content
Twitter: @ChessForge for announcements and chess tips
YouTube: ChessForge channel for tutorials and gameplay
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Chess.com for inspiration and setting the standard for online chess
Lichess for demonstrating the power of open-source chess platforms
Stockfish team for the incredible chess engine
Chess.js contributors for the robust chess logic library
Our amazing community of contributors who make ChessForge possible

Check the FAQ
Search existing Issues
Create a new issue with detailed information
Join our Discord for real-time help
Happy Chess Playing! ♟️

"Chess is the struggle against error." - Johannes Zukertort

