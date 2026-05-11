# Hydrogen & HAPS Competitor Intelligence

A living repository tracking the global competitive landscape in **hydrogen-powered flight** and **High Altitude Pseudo-Satellites (HAPS)**. Includes an interactive dashboard for exploring companies by location, category, and status.

---

## What's In This Repo

| File | Description |
|------|-------------|
| `index.html` | Interactive dashboard with world map + filterable company table |
| `competitors.csv` | Master data file — source of truth for all company records |
| `README.md` | You're reading it |

---

## The Dashboard

Open `index.html` in any browser (or visit the GitHub Pages URL if enabled) to explore:

- **World map** with color-coded pins — cyan for Hydrogen Flight, orange for HAPS
- **Click any pin** to see a company popup with blurb, location, status, and website
- **Click any table row** to fly the map to that company's headquarters
- **Filter** by category (H₂ Flight / HAPS) or status (Active / Inactive)
- **Search** by company name, country, city, or technology focus
- **Sort** any column in the data table

---

## Coverage

### ⚡ Hydrogen Flight
Companies developing hydrogen-powered aircraft, with an emphasis on hydrogen propulsion systems — both fuel cell (electric) and combustion approaches.

Includes: ZeroAvia, Airbus ZEROe, H2FLY, Cranfield Aerospace Solutions, Beyond Aero, Stralis Aircraft, GKN Aerospace (H2 GEAR), Rolls-Royce, CFM International, Destinus, Joby Aviation, United Therapeutics, Universal Hydrogen

### 🛰 HAPS (High Altitude Pseudo-Satellites)
Stratospheric platforms operating above weather and air traffic — solar-electric, hydrogen-powered, and balloon-based systems used for connectivity, surveillance, and earth observation.

Includes: Aalto HAPS (Zephyr), SoftBank HAPSMobile, Skydweller Aero, BAE Systems (PHASA-35), Sceye, Thales Alenia (Stratobus), Stratospheric Platforms, AeroVironment, Aerostar, Near Space Labs, Prismatic

---

## Updating the Data

All company data lives in `competitors.csv`. To add or update a company, edit the CSV directly — the dashboard reads from it automatically.

### CSV Column Reference

| Column | Description |
|--------|-------------|
| `name` | Company or program name |
| `category` | `Hydrogen Flight` or `HAPS` |
| `subcategory` | Technology focus (e.g. Fuel Cell Propulsion, Solar-Electric Fixed Wing) |
| `city` | Headquarters city |
| `country` | Headquarters country |
| `lat` / `lng` | Coordinates for map pin placement |
| `founded` | Year founded or program launched |
| `status` | `Active` or `Inactive` |
| `blurb` | 1–2 sentence description shown in map popup and table |
| `website` | Company or program website URL |

---

## Hosting with GitHub Pages

To make the dashboard publicly accessible as a URL:

1. Go to **Settings** → **Pages**
2. Under *Source*, select **Deploy from a branch**
3. Choose `main` branch and `/ (root)` folder
4. Click **Save**

Your dashboard will be live at:
`https://rachel-wallstrom.github.io/Hydrogen-and-HAPS-Competitors/`

---

## Last Updated

May 2026 · Maintained by [@rachel-wallstrom](https://github.com/rachel-wallstrom)
