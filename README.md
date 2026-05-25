# my_first_project
# COVID-19 Data Analysis Project

## 📌 Project Overview
This repository contains a data science project focused on analyzing global COVID-19 data. Using Python and Jupyter Notebooks, the project cleans, visualizes, and tracks the progression of confirmed cases, recoveries, and fatalities worldwide.

## 📊 Datasets Used
* `covid_19_confirmed_raw.csv` - Global confirmed case data.
* `covid_19_deaths_raw.csv` - Global mortality data.
* `covid_19_recovered_raw.csv` - Global recovery data.

## 🛠️ Tech  & Tools
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn (or whichever ones you used!)

## 🚀 Key Insights & Features
* Data cleaning and preprocessing of raw time-series data.
* Visualizations showing growth rates and trends across different countries.

 ## The Data Tells Us
The Biggest Outbreaks:
When looking at total cases over the whole period, the US recorded the highest numbers, followed closely by India and Brazil.

## Behind the Scenes (Data Cleaning)
Reshaped the Rows: 
Flipped the data from a messy 498-column layout into a clean, easy-to-read timeline using Pandas .melt().

Fixed missing Data:
filled missing tracking values using smart forward-filling (.ffill()) so the charts didn't have random gaps.

Cleaned Up Blank Labels:
Found empty spaces in the region column and grouped them cleanly under an 'All Provinces'.






