# Online Multiplayer Game Platform

A scalable online multiplayer platform featuring real-time gameplay (Tic-Tac-Toe, Connect Four), matchmaking, persistent leaderboards, and a multi-threaded TCP client-server architecture with SQLite database integration built in Java.

## Features
- Real-time multiplayer gameplay (Tic-Tac-Toe, Connect Four)
- Multi-threaded TCP client-server architecture with session handling
- Game-to-server integration supporting concurrent gameplay
- Persistent leaderboard using SQLite
- JavaFX-based user interface

## Contributions
- Developed core game logic for Tic-Tac-Toe and Connect Four
- Implemented rules and validation systems to ensure correct gameplay
- Integrated game modules with the server for real-time multiplayer functionality
- Contributed to UI interaction and game rendering using JavaFX
- Collaborated within a multi-team architecture to ensure system-wide compatibility

## Tech Stack
- Java (JDK 25)
- JavaFX
- Maven
- SQLite
- TCP Networking

## Running the Project

Client:
```bash
./mvnw clean compile
./mvnw clean javafx:run
```

Server:
```bash
./mvnw -f server/pom.xml exec:java
```

## Notes
- The server runs on TCP port 14001
- Client and server must be on the same network for testing
