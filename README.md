# IMD Rainfall Statistics Analysis (2017 & 2018)

## Overview

This project performs statistical analysis on the **India Meteorological Department (IMD) High Spatial Resolution (0.25° × 0.25°) Daily Gridded Rainfall Dataset** for the years **2017** and **2018**.

The project reads binary `.grd` files, processes rainfall data, computes descriptive statistics, and exports the results into CSV files for further analysis.

---

## Dataset

**Source:** India Meteorological Department (IMD)

Dataset:
- High Spatial Resolution Daily Gridded Rainfall Data
- Resolution: **0.25° × 0.25°**
- Grid Size: **135 × 129**
- Unit: **Millimeters (mm)**

Reference:

Pai, D.S., Sridhar, L., Rajeevan, M., Sreejith, O.P., Satbhai, N.S., & Mukhopadhyay, B. (2014).

Development of a new high spatial resolution (0.25° × 0.25°) long period daily gridded rainfall dataset over India.

MAUSAM, 65(1), 1–18.

---

## Project Structure

```
IMD-Data-Processing/
│
├── data/
│   ├── 2017/
│   │   └── Rainfall_ind2017_rfp25.grd
│   │
│   └── 2018/
│       └── Rainfall_ind2018_rfp25.grd
│
├── notebook/
│   └── Rainfall_Statistics_Analysis.ipynb
│
├── outputs/
│   ├── 2017/
│   └── 2018/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Features

- Read IMD Binary (.grd) files
- Handle missing values
- Overall statistical analysis
- Daily rainfall statistics
- Monthly rainfall statistics
- CSV export
- Data visualization

---

## Statistics Computed

### Overall Statistics

- Mean
- Median
- Standard Deviation
- Variance
- Minimum
- Maximum
- Range
- Percentiles

### Daily Statistics

- Daily Mean
- Daily Median
- Daily Standard Deviation
- Daily Variance
- Daily Minimum
- Daily Maximum

### Monthly Statistics

- Monthly Mean
- Monthly Median
- Monthly Standard Deviation
- Monthly Variance
- Monthly Minimum
- Monthly Maximum
- Monthly Total Rainfall

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/IMD-Data-Processing.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Run

Open the notebook

```
notebook/Rainfall_Statistics_Analysis.ipynb
```

Run all cells.

---

## Output

Results are automatically saved in

```
outputs/
    2017/
    2018/
```

Example outputs

- overall_statistics.csv
- daily_statistics.csv
- monthly_statistics.csv

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## License

This project is licensed under the MIT License.

---

## Author

Madhura Borikar

B.Tech Computer Science & Engineering

Jhulelal Institute of Technology