# Global Terrorism Data Analysis

This project performs an Exploratory Data Analysis (EDA) on a global terrorism dataset, with the goal of uncovering insights into terrorism trends, patterns, and outcomes worldwide. The analysis covers data cleaning, statistical analysis, and visualizations that provide insights into the nature and impact of terrorist attacks over time.

## Project Overview

The dataset used in this analysis includes detailed records of global terrorist incidents, including information on the location, type, and success rate of attacks, as well as casualty figures. This analysis is aimed at answering key questions such as:

- **How have terrorist attack trends changed over time?**
- **What types of attacks are most frequent and successful?**
- **What are the most affected regions, and what are the casualty patterns by attack type?**

## Key Findings

1. **Trends Over Time**: Terrorist incidents saw a sharp increase in 2014, with subsequent declines potentially linked to global counter-terrorism measures.
2. **Attack Success Rate**: Success rates vary significantly by attack type, with certain methods achieving consistently higher rates of success.
3. **Casualties and Impact**: Certain attack types and regions experience higher casualty rates, highlighting areas for focused security measures.

## Directory Structure

- `data/`: Contains the raw and cleaned dataset files.
- `scripts/`: Includes R Markdown files for data cleaning and EDA (`Global_terrorism_datacleaning.Rmd` and `my_eda.Rmd`).
- `outputs/`: Stores the generated visualizations and summary reports.
- `README.md`: Project overview and instructions (this file).

## Requirements

This analysis requires R and the following R packages:
- `tidyverse`
- `readxl`
- `janitor`
- `openxlsx`

To install these packages, run the following code in your R console:

```r
install.packages(c("tidyverse", "readxl", "janitor", "openxlsx"))
```
## Usage

### Step 1: Data Cleaning

The `Global_terrorism_datacleaning.Rmd` file performs essential data cleaning steps, including:

- Renaming columns for readability
- Handling missing values
- Standardizing formats for consistency

**To run the data cleaning script:**

1. Open `Global_terrorism_datacleaning.Rmd` in RStudio.
2. Knit the file to generate the cleaned dataset.
   
### Step 2: Exploratory Data Analysis

The `my_eda.Rmd` file conducts the EDA, producing insights through visualizations and summary statistics. The analysis includes:

- Time trends of attack frequencies and success rates
- Casualty analysis by attack type
- Regional distributions of attack incidents

**To run the EDA script:**

1. Open `my_eda.Rmd` in RStudio.
2. Knit the file to generate an HTML report with visualizations and findings.

## Visualizations

The analysis generates various visualizations, including:

- **Attack Frequency Over Time**: A line chart showing the trend of terrorist incidents per year.
- **Success Rate of Attacks by Year**: A line plot indicating the annual success rate of terrorist attacks.
- **Casualties by Attack Type**: A bar plot displaying average casualties per attack type, highlighting the deadliest methods.

## Contributing

Contributions are welcome! If you would like to add new analyses, enhance visualizations, or improve data cleaning techniques, feel free to open an issue or submit a pull request.

## Acknowledgments

This analysis was made possible with data from the [Global Terrorism Database (GTD)](https://www.start.umd.edu/gtd/).


