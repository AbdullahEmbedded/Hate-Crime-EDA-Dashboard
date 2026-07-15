# Hate Crime EDA Dashboard Project

## Overview
This project loads the exact raw dataset file, cleans it with Pandas, and creates a professional Gradio dashboard.

## Dataset Rule
Do not rename the dataset file. Keep it here:

```text
data/hate_crime.csv
```

## Project Structure

```text
dashboard_project/
├── data/
│   └── hate_crime.csv
├── notebooks/
│   └── analysis.ipynb
├── app.py
├── charts.py
├── filters.py
├── requirements.txt
└── README.md
```

## Install Dependencies

```powershell
py -m pip install -r requirements.txt
```

## Run Dashboard Locally

```powershell
py app.py
```

Open this in browser:

```text
http://127.0.0.1:7861
```

Do not open `http://0.0.0.0:7861` in the browser.

## Dashboard Features
- Data cleaning report
- Raw data preview
- Cleaned data preview
- KPI summary cards
- Multi-select state filter
- Category filter
- Numerical range filters
- Search/text filter
- Reset filters button
- Download filtered CSV
- Pie chart
- Histogram
- Line chart
- Bar chart
- Scatter plot
- Box plot
- Heatmap
- Area chart
- Count plot
- Violin plot
- Bonus bubble chart

## Deployment on Render

Build command:

```bash
pip install -r requirements.txt
```

Start command:

```bash
python app.py
```

## Deployment on Railway

Start command:

```bash
python app.py
```
