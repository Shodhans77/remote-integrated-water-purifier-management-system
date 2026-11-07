# Remote Integrated Water Purifier Management System

A self-contained virtual demonstration website for the final-year engineering project. It uses plain HTML, CSS and JavaScript; no build tools, dependencies, backend, ESP32 connection, MQTT broker or physical sensor connection are required.

## Run the website

1. Open a terminal in this folder.
2. Run `python -m http.server 8000`.
3. Open `http://localhost:8000` in a browser.

You can also open `index.html` directly, though a local server is recommended for predictable browser behavior.

## Project files

- `index.html` — page content and SVG purifier model.
- `styles.css` — layout, responsive styles, model styling and animations.
- `app.js` — component data, navigation, dashboard values and fault simulations.

## Demonstration behavior

All readings are simulated in the browser. Fault simulation changes dashboard cards, chart score, device status, phone values and notification history. Reset restores the initial demonstration state. No data leaves the browser.

Component GPIO pins and wiring details are intentionally described as configurable or to be verified against the physical build. The 12V normally closed solenoid valve appears only as optional / planned hardware.
