---
output:
  html_document:
    df_print: paged
knit: (function(inputFile, encoding) { rmarkdown::render(
    inputFile,
    encoding = encoding,
    output_dir = "docs",
    output_file='index.html'
  ) })
---

## Final project: USDA cheese data

### This is my final project for a class called Reporting with Data. I'm currently in the process of analyzing cheese data from the USDA, including prices and storage holdings.

[Cleaning notebook](https://athenahawkins.github.io/athena-final/01-cleaning.html)

- In this notebook, I imported a folder filled with yearly cheese storage and price data dating from 2000 to the present. I clean the data, and use the yearly average CPI to adjust the price data for inflation (into 2015 dollars).

[Analysis/Visuals notebook](https://athenahawkins.github.io/athena-final/02-analysis.html)

- I'm still working on creating visualizations in my analysis notebook.

- I created [this visualization](https://github.com/athenahawkins/athena-final/blob/main/plot2.pdf) for each types of cheese and their prices over time, adjusted for inflation.
