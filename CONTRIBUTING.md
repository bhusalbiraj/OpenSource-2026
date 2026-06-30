# Contributing to PDSC

Thanks for your interest in contributing! This project is the official website for **PDSC**, built with **React + TypeScript + Vite**.

## Prerequisites

- [Node.js](https://nodejs.org/) 18+ and npm

## Running the Project

```bash
# 1. Clone the repo
git clone <repo-url>
cd PDSC-Official-main

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run dev
```

The app will be available at the local URL printed in your terminal (usually http://localhost:5173).

### Other Commands

| Command           | Description                          |
| ----------------- | ------------------------------------ |
| `npm run dev`     | Start the development server         |
| `npm run build`   | Type-check and build for production  |
| `npm run preview` | Preview the production build locally |
| `npm run lint`    | Run ESLint                           |

## Contributing Guidelines

1. **Fork** the repository and create a branch from `main`:
   ```bash
   git checkout -b feat/your-feature-name
   ```
2. **Make your changes.** Keep them focused and small where possible.
3. **Lint before committing** to keep the codebase clean:
   ```bash
   npm run lint
   ```
4. **Write clear commit messages** describing what changed and why.
5. **Open a pull request** against `main` with a short description of your change. Link any related issues.

## Project Structure

```
src/
├── assets/         # images, fonts, and data (JSON)
├── components/     # reusable UI components
├── sub_components/ # smaller building-block components
├── pages/          # route-level pages
├── css/            # stylesheets
└── utils/          # helper functions
```

## Code Style

- Follow the existing patterns in the codebase.
- TypeScript is used throughout — keep things typed.
- Ensure `npm run lint` and `npm run build` pass before opening a PR.

## Questions?

Reach out at [pdsc.nepal@gmail.com](mailto:pdsc.nepal@gmail.com).
