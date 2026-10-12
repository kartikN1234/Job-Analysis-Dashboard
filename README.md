# 📊 Job Analysis Dashboard | Power BI

## 📌 Overview

The Job Analysis Dashboard is an interactive Power BI project designed to analyze job-market data and identify insights into job roles, salaries, experience levels, employment types, locations, and in-demand skills.

The dashboard helps users explore employment trends, understand salary distributions, and identify skills associated with different job roles using interactive visualizations.

## 🎯 Objectives

- Analyze job opportunities across different job roles and experience levels.
- Explore salary distributions across job titles and companies.
- Understand employment types and remote-work opportunities.
- Identify in-demand skills across different job roles.
- Analyze job opportunities across cities, countries, and regions.
- Present job-market insights through interactive Power BI visualizations.

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and data visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and calculations
- **CSV Files** – Data sources

## 📂 Dataset

The project uses five CSV files:

| File | Description |
|---|---|
| `Jobs.csv` | Job titles, experience levels, employment types, salaries, remote-work ratios, and posting dates |
| `Companies.csv` | Company names, sizes, industries, and ratings |
| `Locations.csv` | Cities, countries, and geographical regions |
| `Skills.csv` | Skill names associated with job opportunities |
| `Job_Skills.csv` | Relationships between jobs and their required skills |

## 📈 Dashboard Features

### 1. Job Market Analysis
- Explore job opportunities by job title.
- Compare opportunities across experience levels.
- Analyze employment types, including full-time, contract, and internship roles.

### 2. Salary Analysis
- Explore salary distributions across job roles.
- Compare salaries across companies and experience levels.
- Identify differences in compensation across job categories.

### 3. Skills Analysis
- Identify skills associated with different job roles.
- Explore technical skills such as Python, SQL, TensorFlow, Machine Learning, and Cloud Computing.
- Understand the relationship between job titles and required skills.

### 4. Location Analysis
- Analyze job opportunities across cities and countries.
- Explore regional job-market distributions.
- Compare opportunities across geographical locations.

### 5. Remote Work Analysis
- Analyze remote-work ratios across job opportunities.
- Compare remote-work arrangements across job roles.

## 🔄 Data Modeling & Transformation

The project organizes data from multiple CSV files to support job-market analysis.

The data model includes:
- Job information
- Company information
- Location information
- Skill information
- Job-to-skill mapping

Power Query can be used to clean and transform the source data, while relationships between tables enable cross-filtering and interactive analysis.

DAX measures can be used to calculate analytical metrics and support dashboard visualizations.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install [Power BI Desktop](https://www.microsoft.com/power-platform/products/power-bi/desktop).
3. Open `Job Analysis.pbix`.
4. If prompted, update the source file paths to match the location of the CSV files on your computer.
5. Refresh the data if required.
6. Explore the dashboard using its visualizations and filters.

## 📁 Project Structure

```text
Job Analysis Dashboard/
│
├── Job Analysis.pbix
├── Jobs.csv
├── Companies.csv
├── Locations.csv
├── Skills.csv
├── Job_Skills.csv
└── README.md