# Focuslist — React To-Do App

A clean, minimal task manager built with React to practice component-based architecture, state management, and hooks.

**Live demo:** _add your GitHub Pages link here after deploying_

## Features

- Add, complete, and delete tasks
- Filter by All / Active / Completed
- Progress bar that updates in real time as tasks are completed
- Data persists across sessions using `localStorage`
- Fully responsive, accessible (keyboard focus states, ARIA labels)

## Tech Stack

- React 18 (functional components + hooks: `useState`, `useEffect`, `useMemo`)
- Vanilla CSS (custom design system, no framework)
- LocalStorage for persistence

## What I Practiced

- Managing component state with `useState` and derived state with `useMemo`
- Side effects and persistence with `useEffect`
- Controlled form inputs
- Conditional rendering and list rendering with keys
- Component-level accessibility (focus-visible states, ARIA labels)

## Run Locally

This project has no build step — just open `index.html` in a browser, or serve it with any static server:

```bash
npx serve .
```

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to the `main` branch, root folder
4. Your app will be live at `https://<username>.github.io/<repo-name>`
