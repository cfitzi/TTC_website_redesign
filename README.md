# The Tech Collective — Data, AI & Analytics

A Vite-powered static page for the “What we do → Data, AI & Analytics” redesign.

## Requirements
- Node.js 18+
- npm registry access (configured via `.npmrc` in this repo)

## Run locally
```bash
npm install
npm run dev
```

Vite will print the local development URL (typically http://localhost:5173).

## If dependency install is blocked
If your environment blocks package installs, confirm registry access:
```bash
npm config set registry https://registry.npmjs.org/
```

## Build for production
```bash
npm run build
npm run preview
```
