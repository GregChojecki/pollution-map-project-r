🌍 Pollution Map (R Markdown + Shiny App)

This project showcases the development of an interactive pollution map built in R using R Markdown and Shiny.
The R Markdown file (Pollution_html.Rmd) documents the full workflow — from data preparation to the final interactive application — and includes a complete Shiny app that launches at the end of the knitted HTML.

🔧 App Features
🗺️ Tab 1 — World Overview Map

Shows all cities included in the dataset

Each city is represented by a colored marker, where color indicates the pollution level

Provides a quick global comparison of air quality

📍 Tab 2 — City Explorer

A dropdown menu allows the user to select any city

The map automatically zooms to the selected city

A side panel displays detailed pollution metrics for the chosen location

Helps users understand city-specific pollution levels in depth

📂 Repository Structure
pollution-map-project-r/
├── Pollution_html.Rmd       # Full analysis + final Shiny app
├── data/
│   └── cities_coord.rds     # Preprocessed dataset (backup for Kaggle file)
└── README.md

▶️ How to Run
Option 1 — Knit the R Markdown

Open Pollution_html.Rmd in RStudio and click:

Knit → Knit to HTML

This produces:

A rendered HTML document showing the project development

A Shiny app window launching automatically at the end

Option 2 — Run only the Shiny app

Scroll to the final code chunk in the Rmd (the Shiny code) and run it manually.

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

Spatial visualization techniques

Integrating Shiny inside an R Markdown workflow

Pollution data preprocessing

Interactive user-driven exploration of environmental data
