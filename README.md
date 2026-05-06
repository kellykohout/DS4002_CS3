# DS4002_CS3
This repository contains the deliverable, data, and reference materials necessary to complete CS3. It is about Timeseries data of PM2.5 levels across different NY community district populations. 

## Contents:
- Hook document 
- Rubric
- Various Materials (data, code, articles, references)

Software and Platform
Type(s) of software used: GitHub, STL decomposition [1]

Necessary add-on packages: pandas, matplotlib, seaborn, statsmodels.tsa, scipy, re,

The platform: Windows/ Mac

Map of Documentation

```text
DS4002_CS3/
│
├── README.md
│   └── Project overview, reproduction instructions, and navigation guide.
│
├── variousMaterials/
│   ├── data/
│   │   ├── Air_Quality (3).csv
│   │   └── Air_Quality_Cleaned (3).csv
│   │
│   ├── scripts/
│   │   ├── data_cleaning_visualizations.ipynb
│   │   └── performed_analysis.ipynb
│   │
│   └── sources/
│       ├── PM2.5 Health Impacts in New York - Pragmatic Environmentalist of New York.pdf
│       └── motivationArticle.pdf
│
├── Hook.pdf
│
├── myCS3Rubric.pdf
│
└── LICENSE
    └── Project usage/license information
```

## Instructions for Reproducing Results
All necessary scripts can be found in /variousMaterials. Run the data_cleaning_visualizations.ipynb and performed_analysis.ipynb found within for the correct output results. 

The top 5 CDs with the highest average PM2.5 are Midtwon, Stuyvesant Town and Turtle Bay, Clinton and Chelsea, Greenwhich Village and Soho, and the Financial District.

## Conclusions Drawn
The average PM2.5 concentration in the environment seems to be decreasing over time (years)

Below are some statistics for the STL decomposition and Mann-Whitney Test:
- Trend Slope for High Population: -0.0433 Low Population: -0.0571 p-value: 0.9296
- Seasonal Amplitude: High Population: 3.1578 Low Population: 2.8952 p-value: 0.7239
- Residual RMSE: High Population: 0.8910 Low Population: 0.7011 p-value: 0.2164

## References
All references can be found in /variousMaterials
