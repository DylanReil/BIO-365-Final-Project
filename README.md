# BIO265 Final Project: A GLOBAL ANALYSIS OF THE INFLUENCE OF LITERACY AND HUMAN DEVELOPMENT INDEX ON TOTAL FERTILITY RATE AND PROJECTED POPULATIONS

## Overview
This repository includes the necessary data and code to reproduce the analysis done for our BIO265 final project, which focuses on a global analysis of the influence of literacy and human development index on total fertility rate and projected populations. 

Using this data and code, you can predict the population trajectories for Uruguay, Nigeria, and the Republic of Korea. You can also plot a correlation analysis to compare the fertility rate with the literacy rate or Human Development Index (HDI). 

## How to Use
To perform this same analysis, first run BIO265_finalproject_import.ipynb to load and preprocess the data. Then, run BIO265_finalproject_scatterplots.ipynb for plotting and correlation analysis of fertility rate vs literacy rate or HDI. The projections_boostrapping.ipynb can be run to generate and plot population projections with 95% confidence intervals for the next 10 years. 

## Layout
### **`Jupyter Notebooks and Code`** 
* **`BIO265_finalproject_import.ipynb`**: Data import, cleaning, and processing into tidy dataframes
* **`BIO265_finalproject_scatterplots.ipynb`**: Correlation analysis and scatterplots with regression
* **`projections_bootstrapping.ipynb`**: Population projection modeling

### **`Data Files`** 
* **`HDI_tidy.xlsx`**: Human Development Index (HDI) data in a tidy format. 
* **`lit_rate_tidy.xlsx`**: Literacy rate data in a tidy format. 
* **`crude_birth_unpopulation_dataportal_20250311132101.csv`**: UN population Division birth rate data for Uruguay, Nigeria, and the Republic of Korea.
* **`crude_death_unpopulation_dataportal_20250311132154.csv`**: UN population Division death rate data for Uruguay, Nigeria, and the Republic of Korea.
* **`migration_unpopulation_dataportal_20250311132823.csv`**: UN population Division migration rate data for Uruguay, Nigeria, and the Republic of Korea.

### Documentation Files

1. **`LICENSE`**: A legal protection of our work.

2. **`README.md`**: This file, which documents our project and GitHub repository structure. 

# License Information

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="github.com/gchure/reproducible_research">
    <span property="dct:title">Griffin Chure</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">A template for using git as a platform for reproducible scientific research</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="github.com/gchure/reproducible_research">
  United States</span>.
</p>
