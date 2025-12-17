# Physical AI & Humanoid Robotics Book

A comprehensive guide to Physical AI and Humanoid Robotics built with Docusaurus.

## About This Project

This book explores the fascinating intersection of artificial intelligence and physical systems, focusing on the design, control, and implementation of humanoid robots that can interact with the real world.

## Installation

```bash
npm install
```

## Local Development

```bash
npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

### Deploy to Vercel

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/final-book&project-name=physical-ai-book&repo-name=physical-ai-book)

The project is pre-configured for deployment on Vercel with the `vercel.json` file.

### Manual Vercel Deployment Steps

1. Fork this repository to your GitHub account
2. Go to [Vercel](https://vercel.com/)
3. Click "New Project" and import your forked repository
4. Vercel will automatically detect this is a Docusaurus project
5. Add any environment variables if needed (none required for this project)
6. Click "Deploy" and your site will be live in seconds

### Alternative Deployment (GitHub Pages)

Using SSH:

```bash
USE_SSH=true npm run deploy
```

Not using SSH:

```bash
GIT_USER=<Your GitHub username> npm run deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

## Features

- 🤖 Comprehensive guide to Physical AI and Humanoid Robotics
- 📚 Well-structured chapters with clear learning objectives
- 🎨 Futuristic, premium UI with light/dark mode support
- 📱 Fully responsive design
- 🔍 Built-in search functionality
- 📖 Easy navigation and reading experience

## Tech Stack

- [Docusaurus](https://docusaurus.io/) - Static site generator
- [React](https://reactjs.org/) - UI library
- [Node.js](https://nodejs.org/) - Runtime environment
- [Vercel](https://vercel.com/) - Deployment platform

## Contributing

Feel free to contribute to this project by submitting issues or pull requests.

## License

This project is open source and available under the [MIT License](../LICENSE).
