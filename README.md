# Weather App

A small React + Vite weather application that displays current weather information and forecasts. Built for clarity and easy local development.

## Features
- View current weather by city
- Responsive UI
- Minimal, component-based code using React + Vite

## Tech Stack
- React
- Vite
- JavaScript / JSX
- CSS

## Project Structure
- `src/` — application source
	- `App.jsx` — main app component
	- `main.jsx` — app entry
	- `components/WeatherApp.jsx` — weather UI
	- `components/WeatherApp.css` — component styles
- `index.html`, `vite.config.js`, `package.json` — build & dev config

## Setup

1. Clone the repo (if you haven't already):
```bash
git clone <repo-url>
cd <repo-folder>
```

2. Install dependencies:
```bash
npm install
```

3. Provide an API key
- The app expects a Vite environment variable for your weather API key.
- Create a `.env` file in the project root with:
```
VITE_OPENWEATHER_API_KEY=your_api_key_here
```
- Replace `your_api_key_here` with your key from a weather API provider (e.g., OpenWeatherMap).

## Run (development)
```bash
npm run dev
```
Open the URL shown in the terminal (usually `http://localhost:5173`).

## Build (production)
```bash
npm run build
npm run preview
```

## Usage
- Enter a city name in the search/input field to fetch current weather.
- Modify components in `src/components` to adapt UI or add features.

## Contributing
- Fork the repo, create a branch for your feature/fix, then open a PR.
- Keep changes focused and include a short description of what you changed.

## Notes & Tips
- Vite requires environment variables to start with `VITE_` to be exposed to client code.
- If you add screenshots, place them in `public/` and reference them in this README.

## License
MIT — see LICENSE file if present.
