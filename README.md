# dianaveronez.github.io
# Diana_CLIM680_project
# Project Title:

## Introduction
Precipitation is a critical component of the Earth's hydrological cycle, influencing water resources, agricultural productivity, and the frequency and intensity of extreme weather events. Understanding precipitation patterns is essential for managing water resources, predicting flood risks, and mitigating the effects of climate change (Smith et al., 2020).

One key factor influencing global precipitation variability is the El Niño-Southern Oscillation (ENSO). ENSO is a coupled ocean-atmosphere phenomenon that drives periodic changes in sea surface temperatures in the tropical Pacific Ocean, significantly affecting global climate systems. During El Niño events, shifts in atmospheric circulation alter rainfall patterns, leading to increased flooding in some regions and droughts in others (Trenberth et al., 2007). Conversely, La Niña events often cause contrasting precipitation anomalies, amplifying the complexity of hydrological responses worldwide (McPhaden et al., 2021).

In the context of Arlington County, Virginia, understanding the interplay between precipitation and ENSO is particularly vital for assessing flood risks. With its urbanized landscape and proximity to water bodies, Arlington is highly susceptible to flooding, especially during extreme precipitation events exacerbated by ENSO-related climate variability. Developing a nuanced understanding of these dynamics can enhance flood risk management, improve urban planning, and foster community resilience (County Climate Action Team, 2023).

## Data
Global Precipitation Climatology Project (GPCP) Monthly Precipitation Data located on the NOAA repository.
Link: https://psl.noaa.gov/repository/entry/show?entryid=9aaab85c-cdd3-44af-810c-12a1b23ccf5d
Date: 	1979-01-01 00:00:00 UTC - 2021-12-01 00:00:00 UTC
Model:	GPCP


https://github.com/dianaveronez/Diana_CLIM680_project/blob/main/README.md

## Code Description and results

### Project Notebook via Github
The files about this project you can find in the link: https://github.com/dianaveronez/Diana_CLIM680_project

### Conda Environment
The climate2.yml file is shown to define the environment needed to run all code successfully.

### Libraries
 To work using code is important to plan all the libraries and modules that will be necessary. In this project, the mean libraries used on the notebook were: xarray as xr, matplotlib.pyplot as plt, numpy as np, cartopy.crs as ccrs, cartopy.mpl.ticker as sticker, scipy.stats, and cartopy.util import add_cyclic_point.
 
### Composites with significance
As we read in the introduction, the ENSO can affect the precipitation.
In the next steps, we will define El Nino, La Nina, or Neutral for the period 2000 until 2018.

 
![image](https://github.com/user-attachments/assets/9719b4f3-b16e-48c6-a194-38c1bfa72405)

                    Picture: SST for 2000 to 2018

To continue, the script analyzes sea surface temperature (SST) data to classify periods as El Nino, La Nina, or Neutral from the year 2000 to 2018. It performs the following tasks:
1. Classifies SST data into El Nino, La Nina, and Neutral categories based on temperature thresholds.
2. Counts the number of time points in each category.
3. Plots the SST data over time, highlighting El Nino, La Nina, and Neutral periods with different colors.
Variables:
- elnino: SST data points classified as El Nino (SST >= 0.5).
- lanina: SST data points classified as La Nina (SST <= -0.5).
- neutral: SST data points classified as Neutral (-0.5 < SST < 0.5).
- counts: List containing the counts of time points in El Nino, La Nina, and Neutral categories.
Plot:
- The SST data is plotted over time with different colors indicating El Nino (red), La Nina (blue), and Neutral (green) periods.

The next picture shows us the results for SST for 2000 - 2018 with El Nino, La Nina, and Neutral Periods.


  ![image](https://github.com/user-attachments/assets/f701136c-445b-4293-a587-c49a27f27c1a)
  Picture: SST for 2000 to 2018 with El Nino, La Nina, and Neutral Pediods.

These analyses allow us to know that in the period we have 53 El Nino, 110 Neutral, and 63 La Nina.

To continue, we upload the Global Precipitation Climatology Project (GPCP) and calculate the mean precipitation anomalies for El Niño, La Niña, and neutral conditions from a dataset.




##  Analysis
 



## Summary, Discussion, and Future Work

## References
Smith, J., Brown, K., & Lee, R. (2020). Hydrology in a changing world: Managing water resources. Springer.
Trenberth, K. E., et al. (2007). The impacts of El Niño and La Niña on precipitation patterns. Journal of Climate Science, 20(1), 123-135.
McPhaden, M. J., et al. (2021). ENSO and global hydrology: A review. Nature Climate Change, 11(3), 181-190.
County Climate Action Team. (2023). Arlington County climate risk assessment report. Available at: Arlington County Report
Murray, D., et al., (2020) Facility for Weather and Climate Assessments (FACTS): A Community Resource for Assessing Weather and Climate Variability. Bull. Amer. Meteor. Soc., 101, E1214–E1224, doi: 10.1175/BAMS-D-19-0224.1
Adler et al. (2016) An Update (Version 2.3) of the GPCP Monthly Analysis. (in Preparation). Huffman, G.J., R.F. Adler, P. Arkin, A. Chang, R. Ferraro, A. Gruber, J. Janowiak, A. McNab, B. Rudolf, U. Schneider, 1997: The Global Precipitation Climatology Project (GPCP) Combined Precipitation Dataset. Bull. Amer. Meteor. Soc., 78(1), 5-20.

## Acknowledgements
 I would like to thank CLIM680 professor for coding assistance and answering question.


https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
