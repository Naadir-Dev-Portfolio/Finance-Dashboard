# Finance Dashboard

![Health Dashboard](screens/Finance_Screen.JPG.JPG)

| Developer & Author | Built                |
|--------------------|----------------------|
| Naadir D           | Dec 2023 – July 2024 |

## Overview

This project is a PyQt6-based finance dashboard skeleton designed to showcase data analytics and interactive UI capabilities. While this code provides the barebones structure, the full application features dynamic, exportable charts, automated data imports, and real-time interactivity.

## Features

- **PyQt6 UI** using QtCharts for bar charts, line charts, and more.
- **Automated Data Imports:** External scripts fetch and preprocess financial data, then programmatically generate charts within QFrame layouts.
- **Interactive Export:** Click on any chart title to export the underlying data to Excel as a CSV.
- **Dynamic Export Functionality:** Context-sensitive export options allow for customized data snapshots.
- **Interactive Elements:** Tooltips, filters, and responsive chart elements enable deep data exploration.

## Technologies

- Python 3.x  
- PyQt6  
- PyQt6-WebEngine  
- QtCharts module  
- pandas, numpy  

## Usage

1. Clone the repository.  
2. Install dependencies with `pip install -r requirements.txt`.  
3. Run the UI:  
   ```bash
   python Ui_financeDashboard.py
   ```

## Screenshot

![Finance Dashboard](screens/finance_dashboard.png)

---

