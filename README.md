# Remote Integrated Water Purifier Management System

This repository contains a multi-building purifier service portal demo and the original engineering project showcase. It uses plain HTML, CSS and JavaScript with no build tools or external runtime dependencies.

## Run locally

1. Open a terminal in this folder.
2. Run `python -m http.server 8000`.
3. Visit `http://localhost:8000`.

## Pages and files

- `index.html` — AquaOps service portal with separate service-provider and customer dashboards.
- `portal.css` — responsive light blue and lavender portal interface.
- `portal.js` — sample buildings, purifier inventory, role views, assignments, faults and local notification behavior.
- `project-demo.html` — original interactive engineering project showcase.
- `styles.css` and `app.js` — styles and interactions for the engineering showcase.

## Demo behavior and limits

The seeded portfolio has two sample buildings. Aqua Heights includes five floor-coded purifier units; the sample resident account is assigned only floors 02 and 05. Two example events are present at start: a TDS fluctuation on floor 02 and a leak on floor 05. The service-provider view can inspect every installation, while the customer view is filtered to assigned purifiers.

Fault controls and assignments update `localStorage` in the current browser only. Alerts are simulated in-app; no email, SMS or WhatsApp is sent. No physical ESP32 or sensors are connected, and no real authentication or server-side access control is implemented. Do not use this demo as an operational monitoring service.
