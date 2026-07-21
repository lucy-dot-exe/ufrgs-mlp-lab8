# MLP - Lab 8

A small React + TypeScript app for registering students ("Alunos"). Built with Create React App, React Router, and React Bootstrap. Student data is persisted to the browser's `localStorage`.

This project was made for a lab assignment in the UFRGS course **Modelos de Linguagens de Programação** (MLP).

Live version: https://lucy-dot-exe.github.io/ufrgs-mlp-lab8/

## Tech Stack

- React 17 + TypeScript
- React Router (`HashRouter`) for client-side routing
- React Bootstrap for UI components
- Font Awesome icons

## Getting Started

Install dependencies and start the dev server:

```
yarn install
yarn start
```

Open [http://localhost:3000](http://localhost:3000) to view it in the browser. The page reloads automatically as you edit files.

## Available Scripts

### `yarn start`

Runs the app in development mode.

### `yarn test`

Launches the test runner in interactive watch mode.

### `yarn build`

Builds the app for production to the `build` folder, minified and ready to deploy.

### `yarn deploy`

Builds the app and publishes the `build` folder to GitHub Pages (via `gh-pages`).

## Project Structure

- [src/App.tsx](src/App.tsx) — routes and all app components (`Homepage`, `Register`)
- [src/index.tsx](src/index.tsx) — app entry point

## Learn More

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). See the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started) and the [React documentation](https://reactjs.org/) for more information.
