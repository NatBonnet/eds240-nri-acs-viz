# EDS 240: Data Visualization & Communication | Homework #2 Visualizing FEMA NRI Data

## Author: Nathalie Bonnet

Instructor: Sam Shanny-Csik

Teaching Assistant: Annie Adams

## Description

This repository contains Nathalie Bonnet's work on homework assignments 2 and 3 for EDS 240. The work on the first of these assignments is housed in HW2.qmd, and the work for HW3 is housed in HW3.qmd. 

### HW2 description
[homework assignment #2](https://eds-240-data-viz.github.io/course-materials/assignments/HW2.html) The aim of the code was to work with Federal Emergency Management Agency (FEMA) National Risk Index (NRI) data to compare trends between California and other U.S. states by county.

### HW3 description
[homework assignment #3](https://eds-240-data-viz.github.io/course-materials/assignments/HW3.html) The aim of this homework was to combine FEMA NRI data with American Community Survey (ACS) data from the U.S. Census Bureau to visualize how climate hazard risk exposure varies across racial / ethnic groups in California. 

## Folders and Files
.gitignore: instructions for how the IDE should not track certain files like .DS_Store

HW[2,3]files: setup information for R

HW[2,3].html: HTML file version of the quarto document information.

HW2.qmd: Quarto document containing all code and written responses to address HW2 questions.

HW3.qmd: Quarto document containing all code and written responses to address HW3 questions. 

README.md: repository documentation

## Data Access
These data are publicly accessible via the FEMA Resilience Analysis and Planning Tool (RAPT) website by accessing the interactive [website link](https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/), selecting 'NRI', and downloading the public CSV file.

ACS data was accessed using the {tidycensus} R package, which is publicly available for users that request an API key. To install {tidycensus} and access The U.S. Census Bureau’s data APIs and return tidyverse-ready data frames:

```
install.packages("tidycensus") 

# enter census API key in .Renviron 
#CENSUS_API_KEY="XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
```
## References

Resilience Analysis and Planning Tool (RAPT) | fema.gov. FEMA. https://www.fema.gov/emergency-managers/practitioners/resilience-analysis-and-planning-tool 
American Community Survey 5-Year Data (2009-2024) | census.gov. U.S. Census Bureau. 
https://www.census.gov/data/developers/data-sets/acs-5year.html