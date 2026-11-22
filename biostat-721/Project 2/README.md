
# Project 2: Air Quality Analysis of Data Obtained from RDU Airport

<!-- badges: start -->
<!-- badges: end -->

## Project Description

This project analyzes air quality measurements collected from an EPA monitoring station at the Raleigh-Durham International Airport (RDU). The goal is to summarize pollutant measurements, explore certain trends over time, and to use R to clean, analyze, and visualize environmental data.

## Data Source

Data was obtained from the U.S. Environmental Protection Agency (EPA) air quality monitoring network at/near RDU. 

The files used for analysis were provided by the course instructor.

The data contains information on carbon monoxide (CO), PM2.5, and ozone (O3) concentrations for the years 2018, 2019, and 2020. For 2020, data collection stopped at April. 


# Repository Structure

```text

biotatistics-coursework/
├── biostat-721/
│   └── Project 2/
│       ├── AQ_2018.csv
│       └── AQ_2019.csv
│       └── AQ_2020.csv
│       └── Project 2.rmd
│       └── Project 2.Rproj
│       └── Project-2.docx
│       └── README.md
└── README.md

```

# Reproducing the Analysis

## Requirements

The project was developed in R and requires the following packages:
- tidyverse
- ggplot2
- lubridate
- dplyr 
- flextable
- lintr

Install the required packages using:
```text

install.packages(c("tidyverse", "ggplot2", "lubridate", "dplyr", "flextable", "lintr""))

```

## Steps
1. Clone/download the repistory.
2. Open the project in RStudio.
3. Ensure the required R packages are installed.
4. Explore and review the data files in the Project 2 folder.
5. Run the R scripts as needed.
6. Knit the report to generate the final output.

# Author

Michelle Liang

# Date

November 22nd, 2026
