# DataCamp Notes

Personal notes and practical examples from DataCamp courses, written as Quarto (`.qmd`) files in R.

## Topics Covered

| File | Topic |
|------|-------|
| `02_importing_intermediate_datacamp.qmd` | Data import (CSV, JSON, SQL, databases) |
| `03_data_cleaning.qmd` | Handling missing values, string manipulation |
| `04_data_manipulation_dplyr.qmd` | Data transformation with `dplyr` |
| `04_1_babynames_dplyr_latvia.qmd` | Case study: baby names analysis |
| `05_join_data.qmd` | Table joins and relational data |
| `06_stats.qmd` | Statistical concepts and methods |
| `07_ggplot2.qmd` | Data visualization with `ggplot2` |
| `08_EDA.qmd` | Exploratory Data Analysis |
| `09_sampling.qmd` | Sampling methods |
| `10_inference.qmd` | Statistical inference |
| `10_modelling.qmd` | Introduction to modelling |
| `99_multiple_regression_titanic.qmd` | Case study: multiple regression |
| `VIM_missing_data_imputation.qmd` | Missing data imputation |
| `caries_europe_map_12yo.qmd` | Case study: dental health mapping |
| `risk_vs_odds.qmd` | Risk vs odds ratios |

## Repository Structure

```
datacamp_notes/
├── *.qmd          # Quarto notebooks (notes + code)
├── datasets/      # Data files used in examples
├── images/        # Images embedded in documents
└── datacamp_notes.Rproj  # RStudio project file
```

## Key R Packages

- **tidyverse** — `dplyr`, `ggplot2`, `tidyr`
- **quarto / rmarkdown** — dynamic documents
- **janitor**, **visdat** — data cleaning
- **DBI**, **RMySQL**, **jsonlite** — data import
- **stringdist**, **fuzzyjoin**, **reclin2** — fuzzy matching & record linkage

## Getting Started

```bash
git clone https://github.com/sergiouribe/datacamp_notes.git
```

Open `datacamp_notes.Rproj` in RStudio, then render any `.qmd` file with the **Render** button or:

```r
quarto::quarto_render("07_ggplot2.qmd")
```

Most files use `pacman::p_load()` which auto-installs missing packages.

## Notes

These are personal learning notes. DataCamp course content belongs to DataCamp.
