# STAT40830-Homework1
# STAT40830 - Assignment 1

**Author:** Vyom Pandey (ID: 24203476)  
**Course:** STAT40830  
**Date:** June 11, 2025  

## Overview

This repository contains the Quarto presentation and supporting materials for **Assignment 1** of the STAT40830 course. The analysis explores key **economic**, **social**, and **environmental** indicators across three countries: **Germany (DEU)**, **Ireland (IRL)**, and the **United States (USA)**.

---

## Indicators Analyzed

- **Life Expectancy at Birth** (years)
- **GDP per Capita** (current US dollars)
- **CO₂ Emissions per Capita** (excluding LULUCF)

---

## Goals of the Analysis

1. Load and standardize country-level indicator data using `data.table`.
2. Compare the breadth and coverage of indicators across countries and time.
3. Visualize key trends using `ggplot2`.
4. Perform:
   - Indicator frequency analysis
   - Correlation analysis (GDP vs Life Expectancy)
   - Multi-indicator time series comparisons
5. Derive cross-country insights and trade-offs between prosperity, health, and sustainability.

---

## Tools and Technologies

- **Quarto** for presentation
- **R** for data manipulation and visualization
- **data.table**: fast data wrangling
- **ggplot2**: elegant, layered graphics
- **Git** and **GitHub** for version control

---

## Project Structure
STAT40830-Assignment1/
├── STAT40830_Assignment1.qmd # Quarto source file for slides
├── STAT40830_Assignment1.Rproj # RStudio project file
├── .gitignore # Files ignored by Git
├── indicators_deu.csv # Germany data
├── indicators_irl.csv # Ireland data
├── indicators_usa.csv # USA data
└── README.md # This file

---

## Commit Summary

- Initial commit with data and setup
- Added correlation analysis between GDP and Life Expectancy
- Added multi-indicator time series comparison

---

## Acknowledgments

Data derived from World Bank and international development indicator datasets.  
Special thanks to instructors and TAs for guidance on project design and feedback.

---

## 📝 License

This repository is for academic purposes and does not include a formal license.
