
# **R Visualization and Analysis Project**

This project is designed for visualizing and analyzing spatial and temporal data 
of GG taxi rides using R. It utilizes a variety of R packages for data manipulation, 
mapping, and interactive dashboards.

---

## **Project Description**

The project focuses on analyzing and visualizing datasets related to Yerevan 
districts and other processed data. The aim is to create meaningful insights.

---

## **Features**

- Interactive dashboards built using **Shiny** and **shinydashboard**.
- Visualizations with **ggplot2** and **gganimate**.
- Spatial data handling and mapping with **sf**.
- Statistical analysis and formatting with **dplyr**.
- Seamless integration of multiple plots with **gridExtra**.

---

## **Data Sources**

The project relies on the following datasets located in the `data` directory:
1. **Yerevan-districts**: Contains spatial data for districts in Yerevan.
2. **gg_all.rda**: Consolidated dataset for analysis.
3. **gg_processed_data.RData**: Pre-processed data for visualization tasks.

These datasets must be loaded for the project files (R Markdown and R scripts) 
to run correctly.

---

## **Installation**

Follow these steps to set up the project:

   ```
1. Open RStudio and set your working directory to the project folder:
   ```R
   setwd("path/to/project-folder")
   ```
2. Install the required libraries if not already installed:
   ```R
   install.packages("dplyr", "sf", "formatR", "ggpubr", "jpeg", 
   "classInt", "ggmap", "shiny", "shinydashboard", 
   "gridExtra", "lubridate", "tidyr", "reshape2", "viridis", "stringr")
   ```

---

## **Usage**

1. Load the datasets:
   ```R
   load("data/Yerevan-districts.rda")
   load("data/gg_all.rda")
   load("data/gg_processed_data.rdata")
   ```

2. Run the R scripts or R Markdown files:
   - For R Markdown files:
     Open the `.Rmd` file in RStudio and click **Knit**.
   - Explore the script files by running them. 

3. Explore the interactive dashboards by running the R scripts or by shinyapp.io 
links.

---

## **Technologies and Libraries**

- **Data Manipulation**: `dplyr`, `stringr`
- **Spatial Data**: `sf`
- **Visualization**: `ggplot2`, `gganimate`, `ggpubr`, `gridExtra`
- **Interactive Dashboards**: `shiny`, `shinydashboard`
- **Time Formatting**: `hms`

---

## **Contributing**

Contributions are welcome! If you find any issues or have suggestions for 
improvement, please pull request.

---

