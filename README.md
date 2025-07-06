# C# Trading Engine Server

A modular trading engine server built with C# (.NET Core). This project demonstrates real-time order processing, clean architecture, and modern backend development practices.

## Features
- Modular C# (.NET Core) console application
- Real-time order processing (foundation for trading logic)
- Asynchronous background services
- Dependency injection for service management
- Structured logging and configuration management
- Clean, scalable project architecture

## Getting Started

### Prerequisites

- Visual Studio 2019 or later
- .NET Core 3.1 SDK or later

### Installation

1. **Clone the repository:**
    ```
    git clone https://github.com/scorzion/trading-engine-server.git
    ```
2. **Open the solution** in Visual Studio.
3. **Restore NuGet packages** if prompted.
4. **Build and run** the project.

## Project Structure

├── Program.cs # Entry point and host builder setup
├── Services/ # Core background and trading services
├── Interfaces/ # Service abstractions for extensibility
├── appsettings.json # Configuration file for server settings
└── README.md # Project documentation

## How It Works

This server is designed as a foundation for algorithmic trading systems. It sets up a robust backend with dependency injection, logging, and configuration. The architecture supports further development, such as adding order books, trading algorithms, and client-server communication.

---

Feel free to fork, extend, or contribute!

