# React Hooks

<div align="center">

[![React](https://img.shields.io/badge/React-16.12-61DAFB?logo=react&logoColor=white)](https://react.dev/)
[![Create React App](https://img.shields.io/badge/CRA-3.3.1-09D3AC?logo=create-react-app&logoColor=white)](https://create-react-app.dev/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=000)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![React Router](https://img.shields.io/badge/React%20Router-5-CA4245?logo=reactrouter&logoColor=white)](https://reactrouter.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-4-7952B3?logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Sass](https://img.shields.io/badge/Sass-4-CC6699?logo=sass&logoColor=white)](https://sass-lang.com/)
[![Axios](https://img.shields.io/badge/Axios-0.19-5A29E4)](https://axios-http.com/)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-222?logo=github)](https://pages.github.com/)

</div>

## Overview

Simple GitHub profile finder showcasing React Hooks and Context API. Built with Create React App, client-side routed with React Router, and deployed to GitHub Pages.

## Key Features

- GitHub user search with profile and repositories view
- Client-side routing (`/React-hooks/*`) compatible with GitHub Pages
- Global alerts managed via Context API

## Tech Stack

React 16.12, Create React App 3, JavaScript (ES6+), React Router 5, Axios, Bootstrap 4, Sass

## Architecture

SPA built with CRA. State managed via Context providers (`GithubState`, `AlertState`). Routing with `react-router-dom` and paths scoped for GitHub Pages. Data fetched from GitHub REST API via Axios; no backend services.

## Performance & Accessibility

CRA production build with minification and code-splitting. Basic a11y via semantic HTML and Bootstrap components.

## Quality

- Linting: react-app ESLint • Formatting: none
- Type safety: JavaScript (no TypeScript)
- Tests: React Testing Library configured (no dedicated test suite)
- CI: none

## Prerequisites

- Node.js: `18.17.0`

## Installation

```bash
git clone https://github.com/maxgalchenko/React-hooks.git
cd React-hooks
npm install
```

## Quick Start

```bash
npm start
# Production build
npm run build
# Deploy to GitHub Pages
npm run deploy
```

Open http://localhost:3000

## Available Scripts

- `npm start` – Start the development server (CRA)
- `npm run build` – Build the app for production
- `npm test` – Run tests in interactive watch mode
- `npm run eject` – Eject CRA configuration (one-way)
- `npm run predeploy` – Build prior to deployment
- `npm run deploy` – Deploy the `build` directory to GitHub Pages

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
