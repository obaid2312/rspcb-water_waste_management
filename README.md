# RSPCB Smart Textile Wastewater Monitoring System

A web-based monitoring & digital log book prototype for the **Rajasthan State Pollution Control Board (RSPCB)** to monitor wastewater treatment operations across CETP and ETP facilities in the Balotra textile region.

## Contents

| File | Description |
|------|-------------|
| `index.html` | Cinematic landing page — animated environmental-impact → digital-monitoring transformation (GSAP + SVG). |
| `app.html` | The monitoring platform: dashboard, Individual ETP monitoring, meter-reading submission, approvals, reports and industry master. |

## Features

- **Main Dashboard** with CETP-wise (Balotra / Jasol / Bithuja) filtering and KPI panels.
- **Individual ETP Monitoring** — industry grid, ETP process visualization (ETP → RO → MEE), meter monitoring points, compliance gauges, alerts and analytics charts.
- **Digital Log Book** — 12-hour (8 AM / 8 PM) meter reading submission with photo upload, previous-reading auto-fill, and late/duplicate/capacity alerts.
- **Approvals** — approve / reject readings with reason.
- **Reports** — filterable Reading Log Book with per-reading detail view, CSV export and Print/PDF.
- **Industry Master** — add / edit / delete textile industries.

## Tech

Pure **HTML, CSS and JavaScript** (no build step). Uses **Chart.js** and **GSAP** via CDN, and the browser **localStorage** for data persistence.

## Running

Open `index.html` in a modern browser, or serve the folder with any static web server. An internet connection is required on first load for the CDN assets.

> Presentation prototype built for demonstration purposes.
