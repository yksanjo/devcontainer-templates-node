# Dev Container Template - Node.js & Express

Pre-configured containerized development environment for Node.js and Express applications.

## Features

- **Node.js 20** with npm
- **TypeScript** support
- **ESLint** + **Prettier** for code quality
- **Nodemon** for auto-restart during development
- **PM2** for production process management
- **SQLTools** for database management
- Path IntelliSense
- IntelliCode AI-assisted completion

## Quick Start

1. Copy `.devcontainer` folder to your project root
2. Open the project in VS Code
3. Press `F1` and select **"Dev Containers: Reopen in Container"**

## Configuration

### Ports
- `3000` - Express development server
- `3001` - Alternative development port
- `8080` - General HTTP server
- `9229` - Node.js debugger

### Extensions Included
- ESLint
- Prettier
- PowerShell
- Docker
- TypeScript
- SQLTools
- Path IntelliSense
- IntelliCode

### Post-Create Commands
- Installs TypeScript, Nodemon, and PM2 globally
- Runs `npm install` in your project

## Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [VS Code](https://code.visualstudio.com/)
- [Dev Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## License

MIT
