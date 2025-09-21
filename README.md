# KNUST-Enrollment-Analysis-2016-2017---2021-2022


📄 Full Report: [View Analysis](KNUST_Enrollment_Analysis-2016/2017-2021/2022.html)

## Overview
This project analyzes enrollment trends at Kwame Nkrumah University of Science and Technology (KNUST) from 2016/2017 to 2021/2022, focusing on total student numbers, gender distribution, and year-over-year growth patterns. Drawing from official university data, the study reveals a high  enrollment surge to a peak of 43,275 in 2020/2021, followed by a sharp 32% decline in 2021/2022, with persistent male dominance (average 59.8%). These insights highlight volatility in growth, gender disparities, and potential external influences, informing strategies for sustainable expansion and equity in higher education enrollment.

## Objectives
- Examine total enrollment trends and year-over-year growth rates from 2016/2017 to 2021/2022.
- Analyze gender distribution and comparative growth patterns for male and female students.
- Identify key statistical summaries and implications for enrollment stability and equity.

## Dataset Summary
- **Source**: Quality Assurance & Planning Office, Kwame Nkrumah University of Science and Technology (KNUST), available at https://qapo.knust.edu.gh/resources/basic-statistics-downloads (2025).
- **Sample Size**: 6 academic years (2016/2017–2021/2022).
- **Key Variables**: Academic year, total enrollment, male enrollment, female enrollment, gender percentages, growth rates.

## Methods
- Descriptive statistics (means, percentages, growth calculations) for summarizing enrollment and gender distributions.
- Visualizations including line plots for trends, stacked bar charts for gender proportions, and bar plots for growth rates.
- Comparative analysis of year-over-year changes and averages to assess stability and disparities.

## Key Findings
- Total enrollment grew 183% from 15,285 (2016/2017) to 43,275 (2020/2021), but declined 32% to 29,420 in 2021/2022; average annual enrollment was 30,947, with highest growth in 2017/2018 (80%).
- Males averaged 59.8% of enrollment (15,738 annually), peaking at 62% in 2021/2022, while females averaged 40.2% (13,209 annually), with volatile growth (143.6% in 2017/2018 to -44.9% in 2021/2022).
- Gender gap widened over time, with near-parity only in 2017/2018 (50.9% female); female enrollment showed greater fluctuations.


## How to Reproduce the Analysis
### Requirements
- R (version 4.0 or higher)
- RStudio
- R packages: tidyverse, ggplot2, dplyr

### Steps
1. Clone this repository.
2. Open `analysis.Rmd` in RStudio.
3. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "ggplot2"))`).
4. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). KNUST Enrollment Analysis: 2016/2017 - 2021/2022.
