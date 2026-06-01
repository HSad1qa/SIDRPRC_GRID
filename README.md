# SIDRPRC_GRID
Precipitation (P) data and the affected areas by Tropical Cyclone Sidr
1. The data set folder contains:
    1.1. .csv file containing all grid points for each time step that belong to any country boundary: NI_2007_SIDR_5mmh_all_countries.csv
    1.2. .xlsx files containing all grid points for each time step that belong to a specific country: files with the country name
    1.3. final .xlsx file gives the total grid count for all the countries that received P, grid counts for P>5mm/h, average of the top 90%, 95%, and 99% P and their grid counts, and the minimum range of 75th P (P75), and the average of the top 25% (P75) in a timespan of ±12hr, ±24hr, and ±36hr form landfall: NI_2007_SIDR_Precip_Grid_Summmary.xlsx
2. The Plot folder contains:
    2.1. all the .png files for every timestep showing P on land: prec_on_land folder
    2.2. all the .png files for every timestep showing P on ocean: prec_on_ocean folder
    2.3. scatter plot showing 75%, 90%, 95% and 99% of P for Bangladesh and India: temporal_scatter folder
3. animation of the entire timestep: animation folder
