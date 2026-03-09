[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RFahimi/Group_Research/blob/main/Dataset.ipynb)

# Group Research – Health System Resilience in FCAS

This repository contains the code and data used in our group research project on health system resilience in fragile and conflict-affected settings (FCAS).

The project examines the relationship between health workforce capacity, health expenditure, and population health outcomes across countries over time. In particular, the analysis focuses on how health system capacity is associated with life expectancy in the context of major global shocks such as the 2008 financial crisis and the COVID-19 pandemic.

The repository includes the code used to construct a cleaned country–year panel dataset as well as the input data files required to reproduce that dataset.

## Repository contents

**Dataset construction code**
- `Dataset.ipynb`  
  Python notebook developed and executed in **Google Colab** to clean, reshape, and merge the source datasets into a single panel dataset. The notebook can be opened and run directly in Google Colab using the button above.

**Source data files used to build the dataset**
- `Countries.xlsx`  
  List of countries included in the study sample prepared by AbdulAziz.

- `GDP and health expenditure for FCSL_data.csv`  
  GDP per capita and health expenditure indicators prepared by AbdulAziz.

- `GNI for FCSL_data.csv`  
  GNI per capita data prepared by AbdulAziz.

- `life_expectancy_all_countries.csv`  
  Life expectancy data prepared by Habeeb.

- `MD per 10000.csv`  
  Physicians per 10,000 population dataset prepared by Reza.

- `Nursing and midwifery per 10000.csv`  
  Nurses and midwives per 10,000 population dataset prepared by Reza.

**Final dataset**
- `fcas_final_dataset.csv`  
  The cleaned country–year panel dataset produced by running the dataset construction code. This file is the final merged dataset used for analysis.

## How to reproduce the dataset

1. Open the dataset construction notebook in **Google Colab** using the button at the top of this page.
2. Ensure that the required source data files are available in the working directory.
3. Run the notebook to clean, reshape, and merge the datasets.
4. The script will generate the final dataset (`fcas_final_dataset.csv`).

## Project team
Elites of the University of Warwick.
