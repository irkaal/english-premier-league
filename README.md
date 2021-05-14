# English Premier League Results

## Introduction

This repository contains an R script for scraping historical EPL match results. The dataset is available for download on [Kaggle](https://www.kaggle.com/irkaal/english-premier-league-results).

## Scraping

You can scrape the dataset from
[Football-Data.co.uk](https://football-data.co.uk) with:

```r
# install.packages(
#   c(
#     "arrow",
#     "furrr",
#     "tidyverse",
#     "usethis"
#   )
# )
source("results.R")
```

The csv and parquet files are stored in the data folder.
