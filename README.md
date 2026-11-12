#### Team District 23

This repository uses public data from the Western Pennsylvania Regional Data Center (WPRDC) to make an argument for the "best" neighborhood in Pittsburgh, using metrics our team chose.

**Course: CMPINF 11**

**Canvas Group: Final Project Group 23**

## Team Members

| Name | Email | Individual Notebook |
|---|---|---|
| Yue (Nathan) Li | nal303@pitt.edu | `nathan_housing_price.ipynb` |
| Owen Zhang | haz168@pitt.edu | `owen_bus_access.ipynb` |
| Eddie Witschard | edw53@pitt.edu | `eddie_schools.ipynb` |
| Cooper Ferrance | cof63@pitt.edu | `cooper_crime_notebook.ipynb` |



**Final Project Notebook:** `final_project_notebook.ipynb`

## Metric
We define “best” as the neighborhood that would suit a family moving to Pittsburgh. Each member measured one sub-metric (schools, crime rate, bus access, and housing price), and we averaged the neighborhood rankings into a base score. The neighborhoods that ranked highest in each sub-metric also received bonus points, since those were the family’s top priorities.

## Datasets
| Sub-metric | Dataset | Description | Link |
|---|---|---|---|
| School | Allegheny County Schools (Public, Private, Charter, and Career and Technical Centers) | All Allegheny County schools with data based on the Allegheny County extract of Public and Private school names, addresses and enrollment data | https://data.wprdc.org/dataset/allegheny-county-schools <br> Neighborhood Location Data: https://raw.githubusercontent.com/blackmad/neighborhoods/master/pittsburgh.geojson|
| Crime rate | Pittsburgh Police Arrests (2024-2026) | All Pittsburgh Police arrests from 2024 to October 2026 with data including neighborhood and charge severity (eg., Misdemeanor, Felony)  | https://data.wprdc.org/dataset/pbp_arrest_data_2024_2025|
| Bus access | Pittsburgh Regional Transit Stops | All transit stops in Pittsburgh with data including number of weekday trips, number of routes, and exact location | https://data.wprdc.org/dataset/prt-of-allegheny-county-transit-stops/resource/d6e6ed6e-9220-4a0e-9796-e72d83ce8e7a|
| Housing price | Allegheny County Property Sale Transactions (2024- 2026) | 2024-2026 home sales in Allegheny County with sale prices used to find the average home price in each Pittsburgh neighborhood | https://data.wprdc.org/dataset/real-estate-sales/ https://data.wprdc.org <br> [Parcel Centroids in Allegheny County]:  https://data.wprdc.org/dataset/parcel-centroids-in-allegheny-county-with-geographic-identifiers|

