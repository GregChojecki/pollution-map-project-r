<h1>🌍 Pollution Map (R Markdown + Shiny App)</h1>

<p>
This project demonstrates the development of an interactive <strong>pollution map</strong> built in R using 
<strong>R Markdown</strong>, <strong>Shiny</strong>, <strong>API integration</strong>, and <strong>web scraping</strong>.
</p>

<h2>Workflow Includes:</h2>

<ul>
  <li>Collecting air quality and geographic data via APIs and web scraping</li>
  <li>Cleaning and preprocessing raw data</li>
  <li>Visualizing pollution levels on an interactive world map</li>
  <li>Building a Shiny interface for city-level exploration</li>
  <li>Documenting the full analytical workflow in R Markdown</li>
  <li>Launching a complete Shiny app automatically at the end of the knitted HTML</li>
</ul>

<hr>

<h2>🔧 App Features</h2>

<h3>🗺️ Tab 1 — World Overview Map</h3>
<


Displays all cities included in the dataset

Each city is shown as a colored circle marker representing its pollution severity

Colors are mapped to air quality levels for quick comparison

Data is sourced via APIs and web scraping

Useful for understanding global pollution patterns at a glance

📍 Tab 2 — City Explorer

Dropdown menu to select any specific city

Map automatically zooms to the chosen location

A side panel displays detailed pollutant metrics

Helps users understand city-specific air quality levels

Ideal for deeper investigation of environmental conditions

📂 Repository Structure
pollution-map-project-r/
├── Pollution_html.Rmd        # Full workflow + Shiny app
├── data/
│   └── cities_coord.rds      # Preprocessed dataset (backup for Kaggle data)
├── screenshots/
│   ├── Overview.png          # Screenshot of the global map
│   └── Details.png           # Screenshot of the city-specific tab
└── README.md

🖼️ Screenshots
🌍 Overview Map

📍 City Details View

▶️ How to Run
Option 1 — Knit the R Markdown (recommended)

Open Pollution_html.Rmd in RStudio

Click Knit → Knit to HTML

This will generate:

A rendered HTML explanation of the full workflow

A Shiny application window launching automatically at the end

Option 2 — Run only the Shiny app

Scroll to the final Shiny code chunk inside the R Markdown file and run it manually.

📦 Required R Packages
install.packages(c(
  "dplyr",
  "leaflet",
  "sf",
  "shiny",
  "ggplot2",
  "knitr",
  "rvest",
  "tidyverse",
  "RKaggle",
  "httr",
  "jsonlite"
))

📘 Purpose of the Project

This project demonstrates:

Spatial visualization techniques in R

Combining R Markdown with Shiny for dynamic reporting

Integrating API data and web scraping into a reproducible workflow

Pollution data preprocessing and transformation

Building interactive map dashboards

Presenting a complete, end-to-end analytical story
