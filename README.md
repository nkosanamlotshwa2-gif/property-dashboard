# PropertyOS — Portfolio Intelligence Dashboard

![PropertyOS](https://img.shields.io/badge/PropertyOS-Live-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Properties](https://img.shields.io/badge/properties-15-yellow)

> A lightweight, browser-based property portfolio dashboard built with HTML, JavaScript, and Plotly.js — no backend required.

---

## 🏘️ About This Project

PropertyOS was born out of a need to visualise and track a growing real estate portfolio in Johannesburg, South Africa. Rather than relying on spreadsheets or expensive software, this project delivers a clean, interactive dashboard that loads directly in the browser from a simple JSON file.

This is a personal portfolio intelligence tool designed for property investors who want clarity on:
- How their portfolio is growing over time
- Which properties are delivering the best returns
- How their assets are distributed across property types
- A full ledger view of every property at a glance

---

## 🚀 Live Demo

👉 [View the Dashboard](https://nkosanamlotshwa2-gif.github.io/property-dashboard/dashboard.html)

To explore the dashboard, download the sample data file below and upload it when prompted.

📥 [Download Sample Data](Nkosana_Properties.json)

---

## 📊 Features

- **KPI Strip** — Total properties, portfolio value, total cost, average ROI, and total bedrooms at a glance
- **Purchase Price vs Current Value** — Clustered bar chart showing capital appreciation per property
- **ROI % Ranking** — Horizontal bar chart ranking every property by return on investment
- **Portfolio Composition** — Donut chart breaking down portfolio by property type
- **Price vs Stand Size** — Scatter plot mapping value efficiency across the portfolio
- **Acquisition Timeline** — Area chart showing cumulative portfolio growth since first purchase
- **Property Ledger** — Full sortable table with colour-coded property type badges

---

## 🗂️ Project Structure

```
property-dashboard/
│
├── dashboard.html          # Main dashboard application
├── Nkosana_Properties.json # Sample property dataset
└── README.md               # Project documentation
```

---

## 📁 JSON Data Format

The dashboard accepts any JSON file in the following format:

```json
[
  {
    "Property ID": "P001",
    "Address": "14 Banbury Road",
    "Suburb": "Westdene",
    "Area": "Johannesburg",
    "Property Type": "Freehold House",
    "Bedrooms": 3,
    "Bathrooms": 2,
    "Stand Size (m2)": 744,
    "Purchase Price (R)": 1299000,
    "Purchase Date": "2024-03-15",
    "Current Value (R)": 1365000
  }
]
```

### Supported Property Types
| Type | Colour |
|------|--------|
| Freehold House | 🟡 Yellow-Green |
| Sectional Title Apartment | 🩵 Cyan |
| Student Commune | 🟣 Purple |
| Freehold Cottage | 🟠 Orange |

---

## 🛠️ Built With

- [Plotly.js](https://plotly.com/javascript/) — Interactive chart library
- Vanilla HTML, CSS & JavaScript — No frameworks, no dependencies
- [GitHub Pages](https://pages.github.com/) — Free hosting

---

## 👤 About the Developer

Built by **Nkosana Mlotshwa** — A graduate consultant and Business Analyst based in Johannesburg, South Africa.

This project is part of a broader effort to build practical, data-driven tools for independent property investors in South Africa.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with 💚 in Johannesburg, South Africa*
