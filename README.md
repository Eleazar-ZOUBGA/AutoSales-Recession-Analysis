# Automobile Sales Analytics & Interactive Dashboard

This project is a comprehensive data analysis and visualization web application designed to analyze historical automobile sales data, specifically focusing on the contrasting dynamics between **Recession periods** and **Non-Recession periods**.

The project is structured in two parts: an **Exploratory Data Analysis (EDA)** phase built with Matplotlib and Seaborn, followed by a **Production-Ready Interactive Dashboard** developed using Plotly Express and Dash.

---

## Project Overview

Economic downturns profoundly impact consumer behavior and market structures. This application allows stakeholders to dynamically investigate how macroeconomic indicators—such as GDP, unemployment rates, consumer confidence, and corporate advertising strategies—interact to shape automobile purchasing trends across different vehicle types from 1980 to 2023.

---

## Key Features

### Part 1: Exploratory Data Analysis (EDA)

A series of optimized statistical visualizations designed to extract core market insights:

* **Trend Analysis:** Line charts mapping year-over-year variations in automobile sales during recessions.
* **Segment Breakdown:** Distribution of sales volumes across distinct vehicle categories (e.g., *Superminicars*, *Executivecars*).
* **Macroeconomic Correlations:** Scatter plots tracking the relationship between vehicle prices and transaction volumes, alongside line plots studying the direct impact of spiking unemployment rates.
* **Marketing Budget Auditing:** Aggregated pie charts highlighting strategic shifts in corporate advertising expenditures between crisis and growth cycles.

### Part 2: Interactive Dash Web Application

A dynamic data pipeline transforming static observations into a functional business intelligence tool:

* **Conditional User Controls:** Features a smart dropdown architecture where the year selection menu automatically locks/unlocks based on whether global recession patterns or specific chronological yearly statistics are requested.
* **Recession Report View:** Renders an automated 4-chart analytical matrix tracking sales fluctuations, vehicle type performance, advertising market shares, and unemployment correlations during economic contractions.
* **Yearly Report View:** Generates explicit performance summaries for any targeted year between 1980 and 2023, showcasing historical sales baselines, monthly trends, vehicle breakdown, and marketing asset allocation.

---

## Repository & Layout Structure

The application's interface utilizes a balanced flex-box grid structure that displays graphical charts side-by-side in a responsive layout:

```
├── CarMarket-Recession-Insights.py                  # Core production script containing the Dash layout & callback architecture
├── CarMarket-Recession-Insights.ipynb      # Jupyter Notebook containing raw data cleaning and preliminary Seaborn/Matplotlib plots
└── README.md               # Project documentation and deployment guide

```

---

## Technical Stack

* **Language:** Python 3.12+
* **Data Engineering:** Pandas
* **Data Visualization (Static):** Matplotlib, Seaborn
* **Web & Dashboard Framework:** Dash (Plotly Core, HTML, Components)
* **Interactive Graphs:** Plotly Express

---

## Getting Started & Installation

To run this project locally, follow these simple setup steps:

### 1. Clone the Repository

```bash
git clone https://github.com/Eleazar-ZOUBGA/AutoSales-Recession-Analysis.git
cd AutoSales-Recession-Analysis

```

### 2. Install Dependencies

Ensure you have the required Python libraries installed. You can install them via pip:

```bash
pip install dash pandas plotly seaborn matplotlib more-itertools

```

### 3. Run the Application

Launch the local development web server by executing the core script:

```bash
python app.py

```

### 4. Access the Dashboard

Once the server initializes, open your preferred web browser and navigate to the local host address provided in your terminal console:

```
http://127.0.0.1:8050/

```

---

## Core Analytical Insights

Based on the completed visualization pipelines, several notable economic trends can be derived from the historical dataset:

* **Segment Resilience:** During sharp recession windows, premium vehicle segments experience immediate demand compression, whereas budget-friendly, high-utility options like *Superminicars* exhibit higher volume baselines.

* **Advertising Re-allocation:** Corporate strategy shifts towards defensive budgeting during crises, focusing marketing dollars almost exclusively on price-sensitive models to optimize customer acquisition costs under constrained consumer confidence levels.

* **Unemployment Inversion:** A clear inverse relationship is visible between local unemployment rates and vehicle sales, acting as a crucial leading indicator for market inventory optimization.