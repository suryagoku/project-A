# project-A

This project is an example of integrating a React frontend with a Node.js backend.

## Table of Contents

- [Installation](#installation)
- [Folder Structure](#folder-structure)
- [Dependencies](#dependencies)

## Installation

### Prerequisites

- Node.js installed
- npm or yarn installed

### Steps

- Clone the repository:

  $ git clone https://github.com/username/react-node-project.git

  - Navigate to root directory

  $ cd project-A

  - Install dependencies using npm

  $ npm install

  - Start development server (back-end)

  $ npm start

  - Navigate to client directory

  $ cd project-A/client

  - Install dependencies using npm for front-end

  $ npm install

  - Start development server (front-end)

  $ npm run dev

## Folder Structure

project-A/
|
├── client/
| │
| ├── node_modules/ # Node.js dependencies (generated)
| │
| ├── public/ # Public assets
| │ ├── favicon.ico # Default favicon
| │ └── index.html # HTML template
| │
| ├── src/ # Source code
| │ ├── assets/ # Static assets (images, fonts, etc.)
| │ ├── components/ # React components
| │ ├── App.tsx # Main React app file
| │ └── main.tsx # Entry point TS file
| │ └── index.css # Stylesheet file
| │
| ├── .gitignore # Git ignore file
| ├── package.json # Node.js project dependencies and scripts
| ├── package-lock.json # Node.js project dependencies version control
| ├── vite.config.js # Vite configuration file
| └── yarn.lock # Yarn lock file (if using Yarn)
|
├── node_modules/ # Node.js dependencies (generated)
|
├── server/
| ├── index.js # Entry point
| └── ...
|  
├── .env # Env file
├── .gitignore # Git ignore file
├── package.json # Node.js project dependencies and scripts
├── package-lock.json # Node.js project dependencies version control
└── README.md # Project README file

## Dependencies

### Frontend Dependencies

- **Vite** - A frontend build tool that provides a fast development server and optimized builds.

  - Version : 4.1.0
  - [GitHub Repository](https://github.com/vitejs/vite)

- **React** - A JavaScript library for building user interfaces.

  - Version : 18.2.0
  - [NPM Package](https://www.npmjs.com/package/react)

- **TailwindCss** - Tailwind CSS is a highly customizable, low-level CSS framework that provides utility classes to style your web applications.

  - Version : 3.3.5
  - [NPM Package](https://www.npmjs.com/package/tailwindcss)

  - **Typescript** - TypeScript extends JavaScript by adding types to the language.

  - Version : 4.9.3
  - [NPM Package](https://www.npmjs.com/package/typescript)

### Backend Dependencies

- **Express** - Minimal and flexible Node.js web application framework.

  - Version : 4.18.2
  - [NPM Package](https://www.npmjs.com/package/express)

- **Dotenv** - For loading environment variables from a .env file.

  - Version : 16.3.1
  - [NPM Package](https://www.npmjs.com/package/dotenv)
