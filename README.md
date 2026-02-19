# EVRP-OP Dataset

The EVRP-OP dataset (Electric Vehicle Routing Problem – Ouro Preto) was developed to represent a realistic energy-constrained aerial inspection scenario over historical buildings in the region of Ouro Preto, Minas Gerais, Brazil.

This dataset supports research in:

- Electric Vehicle Routing Problems (EVRP)
- Energy-constrained drone routing
- Reinforcement Learning for routing
- Inspection and monitoring planning

---

## 📍 Scenario Description

The dataset models drone inspections of culturally and historically relevant buildings, including churches, museums, and colonial landmarks located in:

- Ouro Preto
- Mariana
- Itabirito
- Congonhas
- Ouro Branco

The spatial distribution includes:

- Dense historic urban centers
- Intermediate urban zones
- Isolated inspection points requiring longer travel distances

The energy model considers battery consumption proportional to travel distance, with optional recharging stations.

---

## 📂 Repository Structure

├── EVRP-OP_withStation.csv

└─  EVRP-O_noStation.csv

---

## 📐 Data Fields

Each CSV file contains:

- `id` → Unique node identifier
- `latitude` → Geographic latitude
- `longitude` → Geographic longitude
- `estacao` → 1 - It is a station; 0 - It is not a station

---
