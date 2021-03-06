# ETL pipeline for covid infections and vaccinations in Germany

This notebook offers a simple user interface in order to visualize covid infections and vaccinations for each district in Germany.
<p align="center">
  <img width="564" alt="cov" src="https://user-images.githubusercontent.com/74857138/129533860-68a903c6-8cce-49e6-804a-3c2b2ee08e6e.PNG">
</p>

By entering the date and district (Landeskreis) the amount of people who are vaccinated, infected and also the population of the district are displayed. Data is extracted from the following sources in Robert Koch Institut repository:
* Population: https://github.com/robert-koch-institut/SARS-CoV-2_Infektionen_in_Deutschland/blob/master/2020-06-30_Deutschland_Landkreise_GeoDemo.csv
* Vaccination: https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/Aktuell_Deutschland_Landkreise_COVID-19-Impfungen.csv 
* Infection: https://github.com/robert-koch-institut/SARS-CoV-2_Infektionen_in_Deutschland/blob/master/Aktuell_Deutschland_SarsCov2_Infektionen.csv
