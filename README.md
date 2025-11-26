🌍 Pollution Map (R Markdown + Shiny App)

This project showcases the development of an interactive pollution map built in R using R Markdown, Shiny, API integration, and web scraping.
The workflow includes:

Collecting air quality and geographic data via APIs and web scraping

Cleaning and preprocessing data

Visualizing pollution levels on an interactive world map

Building a Shiny interface for city-level exploration

Demonstrating the complete analytical journey inside the R Markdown file

Launching a full Shiny app automatically at the end of the knitted HTML

The final document combines narrative, code walkthroughs, visualizations, and an interactive application.

🔧 App Features
🗺️ Tab 1 — World Overview Map

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
