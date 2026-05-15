# Panchganga Upper Reach River Basin — Hydro Monitoring Network

A web-based interactive hydro-monitoring dashboard developed for real-time visualization and management of Rain Gauge Stations and Radar Water Level Sensors installed across the Panchganga Upper Reach River Basin, Kolhapur, Maharashtra, India.

---

## Overview

This project provides a GIS-enabled interactive monitoring platform for:

* Radar Water Level Sensor Stations
* Rain Gauge Monitoring Stations
* Reference Water Level Observation Points
* Site-based Installation Records
* Instrument Documentation
* Photographic Monitoring Records
* Local Data Storage and Retrieval

The platform has been designed for field-level hydrological monitoring, installation management, and visualization of station infrastructure under the DST-supported river basin monitoring initiative.

---

## Features

### Interactive GIS Dashboard

* Leaflet-based interactive mapping
* Multiple base maps:

  * ESRI Topographic
  * ESRI Satellite
  * ESRI Hybrid
  * OpenStreetMap
  * Google Hybrid

### Station Management

* Radar Water Level Stations
* Rain Gauge Stations
* Reference Monitoring Locations

### Station Information System

Each station includes:

* Station identification
* Coordinates
* River information
* Authority details
* Installation metadata
* Instrument details
* Maintenance records
* Remarks and observations

### Contact Management

* Site-level contact management
* Local authority records
* Institution references

### Installation Records

* Fabrication details
* Installation dates
* Commissioning information
* Service history
* Instrument specifications

### Image Documentation

* Upload station photographs
* Maintain installation image records
* Local browser-based storage
* Lightbox image viewer

### Responsive Design

* Desktop optimized
* Mobile responsive interface
* Dynamic sidebar controls

---

## Technology Stack

| Component       | Technology                         |
| --------------- | ---------------------------------- |
| Frontend        | HTML5                              |
| Styling         | CSS3                               |
| Mapping Library | Leaflet.js                         |
| GIS Tiles       | ESRI, OpenStreetMap, Google Hybrid |
| Data Storage    | Browser LocalStorage               |
| Interface       | Vanilla JavaScript                 |

---

## Project Structure

```bash
├── index.html
├── README.md
└── LICENSE
```

---

## Deployment

This project is deployed using GitHub Pages.

### Live Website

The project can be published using:

```bash
https://<username>.github.io/<repository-name>/
```

---

## Running Locally

Clone the repository:

```bash
git clone https://github.com/<username>/<repository-name>.git
```

Open the project folder:

```bash
cd <repository-name>
```

Run using a local server:

```bash
python3 -m http.server 8000
```

Open in browser:

```bash
http://127.0.0.1:8000
```

---

## Data Storage

The application currently uses browser LocalStorage for:

* Station edits
* Contact details
* Uploaded images
* Installation records

No backend server or cloud database is currently integrated.

---

## Applications

This dashboard can be used for:

* Flood Monitoring
* River Basin Observation
* Rainfall Monitoring
* Hydrological Field Survey
* Instrumentation Tracking
* Research Documentation
* Real-Time Monitoring Systems
* Watershed Monitoring Projects

---

## Research Context

This dashboard was developed as part of a hydro-monitoring and river basin instrumentation initiative focused on improving hydrological observations and monitoring infrastructure within the Panchganga River Basin region.

---

## Future Enhancements

Planned upgrades include:

* Real-time IoT telemetry integration
* Live sensor visualization
* Flood forecasting modules
* Rainfall-runoff analytics
* Hydrograph generation
* Mobile application integration
* Cloud database synchronization
* Sensor health monitoring
* Alert notification systems

---

## License

This project is released under the MIT License.

---

## Developer

Developed by
**Satwik K Udupi**

Research and Development Work
Hydrological Monitoring and GIS-Based Instrumentation Systems

---

## Acknowledgement

Special acknowledgement to the supporting research initiative, institutional collaborators, and field teams involved in the installation and monitoring activities within the Panchganga Upper Reach River Basin.

---
