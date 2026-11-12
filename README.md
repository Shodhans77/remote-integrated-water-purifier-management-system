# Remote Integrated Water Purifier Management System

This repository contains two distinct, self-contained demonstration websites:

- `index.html` — the original interactive engineering project showcase, with the project introduction, 3D purifier model, component explorer, workflow, simulated dashboard and mobile app.
- `portal.html` — the separate AquaOps multi-building service portal with provider/customer views, assigned purifier codes and simulated in-app alerts.

## Run locally

1. Open a terminal in this folder.
2. Run `python -m http.server 8000`.
3. Open `http://localhost:8000/` for the original project showcase, or `http://localhost:8000/portal.html` for the service portal.

Both websites use simulated demonstration data. The portal does not connect to ESP32 hardware, provide real authentication, or send email, SMS or WhatsApp alerts.
