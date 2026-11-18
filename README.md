# RapidRoute AI — Ambulance Route Optimizer

An interactive, browser-based ambulance dispatch simulator powered by a client-side **Random Forest** traffic predictor and **Dijkstra's algorithm** for optimal routing.

## Features

- **AI-Powered Traffic Prediction** — A Random Forest regressor trained on time-of-day, weather severity, and road capacity to predict congestion multipliers.
- **Optimal Route Finding** — Dijkstra's algorithm finds the fastest path through a city network, accounting for predicted traffic conditions.
- **Interactive City Map** — SVG-based network visualization with clickable roads (to block/reopen) and intersections (to change destination).
- **24-Hour Simulation** — Animate dispatch scenarios across all hours to compare ETA trends.
- **Editable Training Data** — Add, remove, or modify training samples and retrain the model in real time.
- **Dark / Light Mode** — Full theme support with smooth transitions.

## Tech Stack

- Pure HTML / CSS / JavaScript — zero dependencies
- Runs entirely in the browser (no server required)

## Live Demo

Deployed on Vercel.

## License

MIT
