# Immigration, Remittances, and Labor Market Outcomes

[![Data Source](https://img.shields.io/badge/Data-World%20Bank%20WDI-orange?style=flat)](https://datacatalog.worldbank.org/search/dataset/0037712)

Applied economics project exploring how migration-related indicators connect to labor markets and development outcomes across countries.

This repository is structured as a portfolio-ready Quarto project. It focuses on a real policy question, uses international development data, and creates a clean foundation for public analysis of migration and economic outcomes.

## Project Snapshot

- Topic: Immigration, remittances, and labor markets
- Coverage: Cross-country development data
- Time period: 2000-2023
- Data source: World Bank World Development Indicators
- Core variables: net migration, remittances, unemployment, GDP per capita
- Tools: R, WDI, tidyverse, ggplot2, Quarto

## Research Question

How are migration-related flows linked to labor-market conditions and development outcomes across countries?

This project is designed around a practical economics question: migration is not only a demographic issue, but also a labor-market and development issue. Countries differ in migration patterns, reliance on remittance inflows, and employment conditions, and those differences can reveal broader development dynamics.

## Why This Project Matters

Migration is central to labor economics, international economics, and public policy. It affects income, labor supply, remittance flows, and economic opportunity.

For an economics portfolio, this repo demonstrates the ability to:

- frame a policy-relevant migration question
- retrieve and clean cross-country indicators in R
- connect migration data to labor-market and development variables
- build exploratory visual analysis
- present results in a reproducible website format

## Data

Source: World Bank World Development Indicators (WDI)

Indicators used in the current project structure:

- `SM.POP.NETM`: Net migration
- `BX.TRF.PWKR.CD.DT`: Personal remittances, received (current US dollars)
- `SL.UEM.TOTL.ZS`: Unemployment, total (% of total labor force)
- `NY.GDP.PCAP.CD`: GDP per capita (current US dollars)

The Quarto source files are designed to support:

- cross-country comparison in the most recent year
- income-group trends over time
- exploratory analysis of remittances and labor-market conditions

## Analytical Approach

This project is exploratory rather than causal. The current source scaffold is built to:

- download migration-related WDI data directly in R
- clean and compare countries using a consistent workflow
- visualize the relationship between remittance inflows and unemployment
- examine how migration indicators vary across income groups and regions

That makes it a strong starting point for deeper extensions such as:

- migration and growth regressions
- regional migration case studies
- remittance dependence analysis
- labor-market adjustment and policy interpretation

## Current Project Structure

The repository now includes:

- `index.qmd` for the main analysis page
- `sources.qmd` for indicator definitions and data notes
- `about.qmd` for project context
- `_quarto.yml` for website configuration
- `styles.css` for basic site styling

## Portfolio Value

This repo strengthens an economics CV because it turns a major real-world issue into a reproducible data project. It shows that you can connect migration, labor markets, and development indicators in a way that is relevant for policy, research, and analytics roles.

A concise CV description for this project could be:

> Built a cross-country migration and development project using World Bank WDI data to examine how remittances, net migration, unemployment, and GDP per capita vary across countries in a reproducible R and Quarto workflow.

## Reproducibility

Install the required R packages:

```r
install.packages(c("WDI", "tidyverse", "ggplot2", "scales", "knitr"))
```

Then render the site locally with Quarto.

## Author

Faran Abbas
Graduate Student, World Economy, Shandong University

- Email: [faranabbas@hotmail.com](mailto:faranabbas@hotmail.com)
- GitHub: [faranabbas-repo](https://github.com/faranabbas-repo)

## Acknowledgment

This project is part of a broader effort to build a stronger economics portfolio with real-world data projects.
