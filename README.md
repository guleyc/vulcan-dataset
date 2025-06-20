# 🪨 Maptek Vulcan Drillhole Dataset (CSV Format)

This repository contains a set of sample geological and geochemical drillhole data files in CSV format, designed for use with **Maptek Vulcan** or other mining and geology software that supports standard drillhole database structures.

These datasets are commonly used in mineral exploration and resource modeling projects. They can be utilized for practice, academic studies, or testing workflows in 3D modeling software.

---

## 📁 Dataset Contents

The dataset includes the following CSV files:

| File Name      | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| `collar.csv`   | Drillhole collar information: hole ID, coordinates (X, Y, Z), depth, dip/azimuth. |
| `survey.csv`   | Downhole survey data: deviation measurements including depth, dip, azimuth. |
| `assay.csv`    | Geochemical assay data: from-to depths and grade values (e.g., Au, Cu, etc.). |
| `lithology.csv`| Lithological data: from-to intervals and associated rock types or codes.     |

---

## 📌 File Structure Notes

- All files are comma-separated (`.csv`).
- Each file contains a common Drillhole ID field (e.g., `HOLEID`, `DHID`) for table linking.
- Depths are in **meters**.
- Coordinate system and elevation units should be verified before use in modeling.

---

## 🧰 How to Use

You can import these files into Maptek Vulcan using the Drillhole Database tools:

```text
Vulcan > DHDB > Create Database from ASCII
Make sure to configure column mappings correctly.

These files can also be used in:

- Leapfrog Geo
- Datamine Studio RM
- Micromine
- Surpac
- Excel / Python / GIS tools

## 📚 Example Applications
- 3D drillhole visualization
- Assay interval plotting
- Lithology interpretation and modeling
- Downhole compositing and statistics
- Resource estimation workflows

## 🛠️ Disclaimer
This is a synthetic or anonymized dataset provided for educational, research, or testing purposes only.
It does not represent real mineral exploration data and should not be used for commercial decisions.

## 📞 Contact
For feedback or questions, please open an issue or visit my website:
https://guley.com.tr
GitHub: @guleyc
