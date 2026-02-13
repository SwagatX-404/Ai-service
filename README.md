# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- - 

# AI Email Reply Writer - Frontend Testing

This repository contains a React-based web application for testing the AI email reply backend. It provides a simple UI to input email details and view generated replies, simulating the Chrome extension's functionality.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This frontend app allows developers to test the backend API without the Chrome extension. It includes forms for email input and displays AI-generated replies.

## Prerequisites
- Node.js 16+ and npm 8+
- Backend server running (from the backend repo)

## Setup
1. Clone the repository:

2. Install dependencies:

## Configuration
1. in App.jsx [http://localhost:8080]

## Running the Application
1. Start the development server: npm run dev
The app will open at `http://localhost:5173`.

2. Build for production:

## Usage
- Navigate to the home page.
- Fill in the email subject, body, and other details.
- Click "Generate Reply" to call the backend API and display the result.

## Testing
- Run unit tests: `npm test`.
- Manual testing: Use the UI to send requests to the backend.

## Deployment
- Deploy to platforms like Vercel, Netlify, or GitHub Pages.
- Example for Vercel: Push to GitHub and connect via Vercel dashboard.

## Contributing
Fork the repo, create a feature branch, and submit a pull request. Use ESLint for code style.

## License
MIT License. See [LICENSE](LICENSE) for details.