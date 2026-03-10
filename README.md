# T&C Farm Website

A simple website for T&C Farm, my family's flower business at Pike Place Market in Seattle, WA. Built as a freelance project.

## Pages

- **Home** — Business home page
- **About** — The farm's story
- **Gallery** — Photos of flowers and the market
- **Contact** — How to get in touch

## Tech Stack

- HTML & Tailwind CSS v4
- Vanilla JavaScript

## Running Locally

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the Tailwind build watcher:
   ```bash
   npm run build
   ```

3. Open `index.html` with Live Server.

> Keep the `npm run build` terminal running in the background while you work so Tailwind recompiles on save.

## Project Structure

```
tcfarm/
├── index.html
├── pages/
│   ├── about.html
│   └── gallery.html
├── css/
│   └── style.css       # Tailwind input
├── dist/
│   └── style.css       # Compiled output (auto-generated)
└── assets/
```