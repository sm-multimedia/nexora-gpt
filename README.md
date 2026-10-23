# Nexora GPT

Nexora GPT is a React landing page for an AI platform. The page introduces GPT-6 through a hero section, feature and capability summaries, partner branding, a blog/library area, calls to action, and a footer.

## Tech stack

- React 19
- Vite 8
- React Icons
- ESLint

## Getting started

### Prerequisites

Install [Node.js](https://nodejs.org/) and npm.

### Install dependencies

```bash
npm install
```

### Run the development server

```bash
npm run dev
```

Vite prints the local URL in the terminal when the server is ready.

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server. |
| `npm run build` | Create a production build in `dist/`. |
| `npm run preview` | Serve the production build locally for preview. |
| `npm run lint` | Run ESLint across the project. |

## Project structure

```text
src/
  components/   Reusable page components, including navigation and feature cards
  containers/   Landing-page sections such as the header, features, blog, and footer
  assets/       Images and partner logos
  App.jsx       Assembles the page sections
  main.jsx      Application entry point
public/         Static files and web app manifest
```

## Build

Create the production bundle with:

```bash
npm run build
```

To inspect that bundle locally:

```bash
npm run preview
```

## Copyright

Copyright Nexora Technologies 2026.