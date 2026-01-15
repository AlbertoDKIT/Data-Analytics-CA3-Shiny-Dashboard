# Cinematic Virtual Production Dashboard

This repository contains the interactive Quarto Dashboard for Part C.

## Main File

- **Dashboard:** `plots.qmd`  
  Interactive dashboard displaying:
  - Production budgets vs. completion dates
  - Asset counts by production and type
  - Crew member participation across productions

## How to Open

1. Open `plots.qmd` in RStudio or Quarto.  
2. Click the “Render” button (ensure `runtime: shiny` is enabled).  
3. The dashboard will run locally with interactive plots and sidebar inputs.  
4. Ensure the database `data/virtual_production.db` is in the `data/` folder.
