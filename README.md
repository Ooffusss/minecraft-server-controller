# Minecraft Server Controller

A web-based Minecraft Server Controller with a dark themed UI that allows for server management, monitoring, and configuration.

## Features

- **Server Dashboard**: View all your Minecraft servers in one place with status monitoring
- **Server Management**: Start, stop, and restart Minecraft servers
- **Console Access**: View real-time server console output and send commands
- **Player Management**: Monitor online players, their locations, and game modes
- **Task Scheduler**: Schedule automated tasks like backups and restarts
- **Performance Monitoring**: Track server CPU, memory usage, and uptime
- **Dark-themed UI**: Modern and clean interface optimized for server management

## Technology Stack

- **Frontend**: React, TypeScript, TailwindCSS, shadcn/ui
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL with Drizzle ORM
- **Real-time Communication**: WebSocket for console output and server monitoring
- **Authentication**: Passport.js with session-based authentication

## Getting Started

### Prerequisites

- Node.js (v18+)
- PostgreSQL database
- Minecraft Server JAR files

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/minecraft-server-controller.git
cd minecraft-server-controller
```

2. Install dependencies
```bash
npm install
```

3. Configure environment variables
```bash
# Create a .env file and add your database connection string
DATABASE_URL=postgresql://username:password@localhost:5432/minecraft_controller
```

4. Run database migrations
```bash
npm run db:push
```

5. Start the application
```bash
npm run dev
```

6. Access the application at `http://localhost:5000`

## Default Login

- Username: `admin`
- Password: `admin123`

## License

This project is licensed under the MIT License - see the LICENSE file for details.