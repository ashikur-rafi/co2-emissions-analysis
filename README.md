# CO₂ Emissions Analysis with Python

## Project Overview

This project explores global CO₂ emissions using Python and data analysis libraries. The analysis focuses on identifying emission patterns, comparing countries, and examining changes in CO₂ emissions over time.

The project was created as part of my journey in learning **Python for Data Analysis**.

## Objectives

- Explore and understand the CO₂ emissions dataset
- Analyze CO₂ emissions by country and year
- Identify countries with high total CO₂ emissions
- Compare CO₂ emissions per capita
- Analyze Bangladesh's CO₂ emissions over time
- Compare Bangladesh, India, Pakistan, and Sri Lanka
- Calculate CO₂ emissions growth between 2000 and 2024
- Create visualizations to communicate findings

## Tools & Technologies

- **Python**
- **Pandas** — data manipulation and analysis
- **NumPy** — numerical calculations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization
- **Jupyter Notebook** — analysis environment

## Dataset

The project uses the **Our World in Data CO₂ dataset**, which contains historical information about CO₂ emissions and related indicators for countries and regions around the world.

The raw dataset is stored locally in the `data/` folder and is excluded from the GitHub repository using `.gitignore` because of its file size.

## Analysis Performed

### 1. Data Exploration

- Loaded and inspected the dataset
- Examined columns and data types
- Selected relevant variables
- Filtered data by year and country

### 2. Global CO₂ Analysis

- Identified the top 10 countries by total CO₂ emissions
- Compared CO₂ emissions per capita
- Calculated CO₂ emissions per capita manually

### 3. Bangladesh Analysis

- Analyzed Bangladesh's CO₂ emissions from 2000–2024
- Identified Bangladesh's highest-emission year
- Visualized Bangladesh's emissions trend

### 4. Country Comparison

Compared CO₂ emissions between:

- Bangladesh
- India
- Pakistan
- Sri Lanka

The comparison includes both total CO₂ emissions and CO₂ emissions per capita.

### 5. Growth Analysis

Calculated the percentage change in CO₂ emissions between **2000 and 2024** for the selected countries.

## Visualizations

The project includes:

- Line charts
- Country comparison charts
- CO₂ per-capita comparisons
- Historical emission trends

## Project Structure

```text
co2-emissions-analysis/
│
├── analysis.ipynb
├── data/
│   └── owid-co2-data.csv
├── .gitignore
└── README.md
```

## How to Run

1. Clone this repository.
2. Make sure Python is installed.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Place the dataset inside:

```text
data/owid-co2-data.csv
```

5. Open `analysis.ipynb` in Jupyter Notebook or VS Code.
6. Run the notebook cells from top to bottom.

## What I Learned

Through this project, I practiced:

- Data loading and exploration with Pandas
- Filtering and sorting datasets
- Working with missing values
- Grouping and reshaping data
- Calculating percentages and growth rates
- Using NumPy for numerical calculations
- Creating charts with Matplotlib and Seaborn
- Working with Jupyter Notebook
- Organizing a data-analysis project with Git and GitHub

## Author

**Md. Asikur Rahman **

Aspiring Data Analyst | Excel | SQL | Python | Pandas | Data Visualization

---

### Data Source

**Our World in Data — CO₂ and Greenhouse Gas Emissions Dataset**
