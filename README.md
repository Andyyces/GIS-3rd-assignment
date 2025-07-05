# GIS-3rd-assignment

Group members: **Tuan Linh Tran**, **Andrea Češková**, **Tobias Gruner**

This repository was created to collaborate on the 3rd Assignment in the "Introduction to Geographic Information Systems" at TUD in the summer semester 2025. We will be analysing the following:

-   Geographic area: Netherlands

-   Research question: **How does the relationship between population density and temperature vary across different land use types around Netherlands?**

-   Data sources:

    -   [Administrative boundaries](https://gadm.org/)

    -   [Temperature data](https://chelsa-climate.org/)

    -   [Land use](https://land.copernicus.eu/en/products/corine-land-cover)

    -   [Population density](https://www.worldpop.org/)

## How to run the analysis

1.  The empirical analysis requries the 4 different datasets as described above. The code to download those can be found in `/R/Data_download.qmd` . All the datasets used are publicly accessible. The data on Land use from Corine is downloaded using API token. This token can be generated after creating an account. After generating, the .json token file should be saved to `/GIS-3rd-Assignment/` as `token.json` . Then the code can be run.

2.  Our analysis can be found in the `/R/Report.qmd` file, which contains source code. This can be also found as a rendered file: `/R/Report.html`
