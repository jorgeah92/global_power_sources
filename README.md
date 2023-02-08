# Global Power Generation Sources
Tableau dashboard of the world's power plants

Link to dashboard on Tableau Public: <https://public.tableau.com/views/GlobalPowerSources_16757399390460/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link>

A dashboard created using Tableau public that displays a map showing the location of power plants throughout the globe, the amount of power generated for the year 2014, the percentage of population with access to energy for 2014, and a pie chart of the energy source used for power generation. The dashboard is interactive by allowing the user to filter the information displayed by country. The data gathered for this project was found in several publicly available locations including other Github projects and energydata.info site. All datasets used for the project were cleaned using python and pandas then saved as csv files for access in Tableau.
 
Included in this repo are links to several publicly available datasets that include various information about energy generation including location of power plants, their power source type, estimated power generation for several years, and access to energy information for several years for a given population type (urban, rural) for each country.
 
`global_power_plant` from <https://github.com/wri/global-power-plant-database>
 
`global_electricity_generation` from [energydata.info](https://energydata.info/dataset/world-electricity-generation-by-country)
 
`pop_energy_access` from [energydata.info](https://energydata.info/dataset/world-global-tracking-framework-2017)
 
*The included datasets are cleaned versions of the original sources saved as `csv`. *

Also included is the notebook used to clean each of the datasets and a copy of the tableau workbook.