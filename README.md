# Big-Data-Analysis-and-project
Project

---

## ⚙️ Installation & Setup

### 1. Prerequisites

install **RStudio** for easier execution.

---

### 2. Required R Packages

The analysis requires the following R packages:

- `tidyverse`
- `readr`
- `cluster`
- `scales`
- `ggthemes`
- `GGally`
- `forecast`
- `zoo`
- `lubridate`
- `caret`
- `randomForest`
- `xgboost`
- `dynlm`

You can install them all at once by running in R:

```r
install.packages(c(
  "tidyverse", "readr", "cluster", "scales", "ggthemes", "GGally", 
  "forecast", "zoo", "lubridate", "caret", "randomForest", "xgboost", "dynlm"
))
```
### 3. Running the Project

Clone the Repository

bash
git clone https://github.com/your-username/part-b-project.git

cd part-b-project

### 4. Place Data in data/ Folder
Ensure the following files are inside the data folder:

- data.csv (air quality data) https://www.kaggle.com/datasets/shrutibhargava94/india-air-quality-data

- GlobalLandTemperaturesByCity.csv (temperature data) https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data

- wfp_food_prices_global_merged_1990-2025.csv (food price data) https://www.kaggle.com/datasets/bassam165/global-food-prices-1992-2025?resource=download

### 5. Open the R Markdown Script

- In RStudio, open proj_part_B.Rmd.

### 6. Knit to PDF or HTML

- Click the Knit button in RStudio to generate the analysis report.
