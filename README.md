# PropertyOS — Portfolio Intelligence Dashboard

![PropertyOS](https://img.shields.io/badge/PropertyOS-Live-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Properties](https://img.shields.io/badge/properties-15-yellow) ![Built With](https://img.shields.io/badge/built%20with-Plotly.js-orange)

> A lightweight, browser-based property portfolio dashboard built with HTML, JavaScript, and Plotly.js with no backend, no server, no cost.

---

## 🏘️ About This Project

PropertyOS started as a personal problem worth solving.

As a property investor managing a growing portfolio across Westdene, Johannesburg, I found that existing tools were either too expensive, too complex, or simply not built for the South African market. Spreadsheets were fragile. Power BI required a paid licence and a backend. Nothing gave me a clean, fast, shareable view of my portfolio without friction.

So I built one.

PropertyOS is a single HTML file that runs entirely in the browser. You drop in a JSON file containing your property data and the dashboard instantly renders six interactive charts, a full KPI strip and a property ledger that you can use with zero setup, zero cost and zero dependencies beyond an internet connection.

It is designed for independent property investors who want clarity on:

- Which properties are delivering the strongest returns
- How portfolio value has grown since the first acquisition
- How assets are distributed across property types
- A clean, professional view they can share with investors, advisors or partners

---

## 🚀 Live Demo

👉 [Open the Dashboard](https://nkosanamlotshwa2-gif.github.io/property-dashboard/dashboard.html)

Download the sample dataset below, then upload it when prompted to explore the full dashboard.

📥 [Download Sample Data](Nkosana_Properties.json)

---

## 📊 Features

- **KPI Strip** : Portfolio value, total cost, unrealised gain, average ROI and total bedrooms at a glance
- **Purchase Price vs Current Value** : Clustered bar chart showing capital appreciation per property, sorted by gain
- **ROI % Ranking** : Horizontal bar chart ranking every property by return on investment
- **Portfolio Composition** : Donut chart breaking down the portfolio by property type
- **Price vs Stand Size** : Scatter plot mapping purchase price against stand size, sized by bedrooms
- **Acquisition Timeline** : Area chart showing cumulative portfolio cost from first purchase to present
- **Property Ledger** : Full table with colour-coded property type badges and inline ROI bars

---

## 🗂️ Project Structure

```
property-dashboard/
│
├── dashboard.html             # Full dashboard — single file, runs in any browser
├── Nkosana_Properties.json    # Sample Westdene portfolio dataset (15 properties)
└── README.md                  # Project documentation
```

---

## 📁 JSON Data Format

The dashboard accepts any JSON file structured as follows:

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

- [Plotly.js](https://plotly.com/javascript/) — Interactive data visualisation
- Vanilla HTML, CSS and JavaScript — no frameworks, no build tools, no dependencies
- [GitHub Pages](https://pages.github.com/) — Free static hosting

---

## 👤 About the Developer

**Nkosana Mlotshwa** is a Graduate Consultant and Business Analyst based in Johannesburg, South Africa, specialising in strategy, risk and data.

He holds an LLB Honours degree from the University of Pretoria (GPA: 71%), alongside professional certifications in Microsoft Power BI, Risk Management from the New York Institute of Finance, and Google Data Analytics. He is currently completing a BSc in Computer Science through the University of London.

His work sits at the intersection of legal and regulatory thinking, risk and data analytics, and systems design with a focus on financial services, banking, property and technology. He approaches business problems the way an engineer approaches a structure: starting with the foundation, mapping the mechanics, and building solutions that scale.

PropertyOS reflects that approach — a practical, data-driven tool built not to impress, but to work.

🔗 [LinkedIn](https://linkedin.com/in/nkosana-mlotshwa763b1a2a1) | 📧 nkosanamlotshwa2@gmail.com

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with 💚 in Johannesburg, South Africa*
