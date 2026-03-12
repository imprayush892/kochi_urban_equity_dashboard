# 🏙️ Kochi Urban Equity Dashboard

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](#)
[![Leaflet](https://img.shields.io/badge/Leaflet.js-Interactive_Maps-green?logo=leaflet)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Bridging the gap between traditional spatial design and computational analysis to visualize transit equity.**

[👉 **View the Live Interactive Dashboard Here**]([INSERT YOUR GITHUB PAGES LINK HERE])

---

## 🚀 The Vision: Making Invisible Data Visible
When critical city data remains locked in static spreadsheets, decision-makers are disconnected from spatial reality. This project transforms raw GTFS public transit data (mdb-1835) and localized wealth indices into a dynamic, zero-dependency policy tool for Kochi, India.

Instead of static reports, this dashboard provides city decision-makers with a living visual narrative. By mapping transit density against demographic wealth, the tool instantly flags **"Double Disadvantage"** zones—neighborhoods suffering from both low economic resources and poor public transit access.

### Key Insights Identified:
* 🚨 **Njarakkal (Double Disadvantage):** Island geography combining Kochi's lowest wealth index (0.20) with near-zero transit access. Represents the most urgent equity gap.
* 🚌 **Transit Dependent Zones:** Areas with lower wealth that heavily rely on public buses. Any service cuts here have disproportionate human consequences.
* 🚗 **Car Dependent Zones:** Higher wealth areas lacking transit coverage, representing missed ridership opportunities.

---

## 🛠️ Methodology & Tech Stack

1. **Data Ingestion:** Automated downloading and processing of MobilityData GTFS feeds using `pandas`.
2. **Computational Analysis:** Calculating route frequencies, dense geometry mapping, and spatial proximity scoring using `numpy` and `scipy`.
3. **Frontend Visualization:** A zero-dependency, highly performant UI/UX built with raw HTML, CSS, JavaScript, and `Leaflet.js` with integrated `simpleheat` rendering.

---

## 💻 How to Run Locally

If you want to dive into the data processing, run the Jupyter notebooks locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/imprayush892/kochi_urban_equity_dashboard.git
   cd kochi-urban-equity
