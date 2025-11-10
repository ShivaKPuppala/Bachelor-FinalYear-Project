# EcoMachining
### *Performance Assessment of Additive-Based Vegetable Oils as Cutting Fluids in Machining*

> **Submitted:** March 2017 — Bachelor of Technology (Mechanical Engineering), GITAM University  
> **Authors:** P. Shiva Kumar, T. Sai Mahith, N. Sai Kiran, T. Sita Rama Raju  
> **Guide:** Dr. R. Padmini (Assistant Professor, Industrial Engineering)

This repository presents a modern, visual, and data-backed version of the 2017 bachelor thesis studying **eco‑friendly cutting fluids** made from **coconut oil (CC)** and **sunflower oil (SF)** enhanced with **maize starch additive (MSA)** under **Minimum Quantity Lubrication (MQL)** during turning of **EN8 steel**.

---

## 📦 Repository Contents
```
EcoMachining/
├─ README.md
├─ references.md
├─ thesis_report.docx  (original source)
├─ experiment/
│  ├─ material_composition_table.csv
│  ├─ en8_mechanical_properties.csv
│  ├─ formulation_diagram.png
│  ├─ machining_setup.png
│  └─ mql_system_schematic.png
├─ results/
│  ├─ thermal_conductivity.csv
│  ├─ tool_wear_data.csv
│  ├─ cutting_temperatures_coconut.csv
│  ├─ cutting_temperatures_sunflower.csv
│  └─ graphs.png
└─ simulation/
   ├─ thermal_analysis.ipynb
   └─ wear_rate_visualization.ipynb
```

> **Theme:** Blue–White (scientific). All generated visuals follow this palette.

---

## 🧪 Experiment Setup (from Thesis)
| Parameter | Specification |
|---|---|
| Work Material | EN8 Steel (080M40) |
| Machine | PSG‑124 Lathe |
| Operation | Turning |
| Tool Holder / Insert | PSLNR 2020 K12 / CNMG120408NC6110 (coated carbide) |
| Speed / Feed / DOC | 560 rpm / 0.17 mm·rev⁻¹ / 0.5 mm |
| Lubrication | MQL @ 10 ml·min⁻¹ |
| Fluids | CC and SF with MSA at multiple concentrations |

---

## 📊 Data (Actual)
- `results/thermal_conductivity.csv` — Thermal conductivity for CC & SF with MSA levels  
- `results/tool_wear_data.csv` — Tool wear (µm) across fluids  
- `results/cutting_temperatures_*.csv` — Time evolution of cutting temperature (°C)

> *Note:* Surface roughness values were not explicitly available as numeric tables in the source; the original report presented them as graphs. This repo includes all available numeric tables verbatim.

---

## 🔎 Findings (from Thesis)
- **CC + 0.1g MSA/100ml** minimized **cutting temperature** and often **tool wear**.  
- **SF variants** tended to yield **better surface finish** (lubricity advantage).  
- Additives improved **thermal conductivity** vs. pure oils, supporting the **eco‑efficient** performance of bio‑fluids.

---

## 🧭 How to Reproduce Plots
Open the notebooks in `simulation/` and run all cells. They pull from CSVs in `results/` and recreate `results/graphs.png`.

---

## 🧠 Citation
> P. Shiva Kumar, T. Sai Mahith, N. Sai Kiran, T. Sita Rama Raju, R. Padmini (2017). *Performance Assessment of Additive‑Based Vegetable Oils as Cutting Fluids in Machining*. GITAM University, Visakhapatnam.

---

## 🪴 License
MIT — Feel free to use with attribution.
