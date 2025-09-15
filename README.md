# SaaS-Contracts-Dashboard- link od demo:- https://drive.google.com/file/d/1nbnXBvWKgTI7r3h-7q4xp2rIEefuXA8s/view?usp=sharing
This scaffold matches the *UI/UX Developer Assignment – SaaS Contracts Dashboard* requirements. It contains a minimal React + Tailwind app with the required pages and mock API files.
SaaS Contracts Dashboard - Starter Scaffold

This scaffold matches the *UI/UX Developer Assignment – SaaS Contracts Dashboard* requirements. It contains a minimal React + Tailwind app with the required pages and mock API files.

## What's included
- React (Vite)
- Tailwind CSS
- Context API for auth
- Routing with react-router-dom
- Mock API JSON files in /public
- Pages: Login, Dashboard, Contract Detail
- Components: Sidebar, Topbar, ContractsTable, UploadModal, ClauseCard
- Simulated uploads (timeout-based)
- README with setup & deployment instructions

## Setup
1. Install dependencies
bash
npm install

2. Start dev server
bash
npm run dev

3. Open http://localhost:5173

## Tech choices & assumptions
- Vite + React for fast dev environment.
- Tailwind CSS for utility-first styling (no inline CSS).
- Context API (AuthContext) for authentication and ContractsContext for contract state.
- Mock API served from /public/*.json — no backend required.

## Deployment
- Push to GitHub and connect to Vercel or Netlify (select the repo and set build command npm run build, publish dist).

## Notes
- Password for mock login: test123 (any username allowed).
- JWT is mocked and stored in localStorage.
- Pagination, search, filters implemented on the client side for the mock data.
