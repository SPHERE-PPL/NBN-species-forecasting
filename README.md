# SPHERE-PPL Forecasting Contest – NBN Atlas Species Occurrence Forecasting


## Introduction

Accurate forecasting of species distributions can help improve our understanding of how species respond to environmental change [Baker et al., 2021](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/1365-2664.70177). This can subsequently support more effective environmental monitoring, informed conservation practices, and improved identification of emerging invasive species trends [Anselmetto et al., 2025](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/1365-2664.13782).

These methods typically require linking species occurrences with environmental conditions and predicting distributions through space and time. The NBN Atlas provides a powerful source of UK biodiversity data, bringing together more than 385 million species occurrence records from over 190 data partners. 

The aim of this contest is to develop a model capable of forecasting species occurrence within a target UK region in 2026.


## Data

The target outcome variable comprises occurrence data for 9 UK species sourced from the [The NBN Atlas](https://nbnatlas.org). 

Participants are encouraged to source and include additional relevant predictor datasets to improve predictive performance. The repository includes several potential starting points:

[COPERNICUS Bioclimate Data](https://cds.climate.copernicus.eu/datasets/sis-biodiversity-cmip5-global?tab=overview)

[LUH2 Land Use Data]( https://luh.umd.edu/index.shtml)

[Elevation data](https://datashare.ed.ac.uk/items/1fe02e91-384b-45b4-be0d-4ec52d6c23fb)

[Soil data](https://isric.org/explore/soilgrids)

Species occurrence data and the provided environmental predictors have been harmonised to a 5 km grid.


## Joining the contest & Getting Started

In order to join the contest, you will need to fork or download the repo.

To fork the repo, simply press the "fork" button, which can be found at the top of this github page. A step-by-step guide can be found [here](https://scribehow.com/shared/Forking_a_SPHERE-PPL_Forecasting_Contest_Repository_on_GitHub__o_bLCyQlTsO0o5YCmGsk8Q).

To download the data without a github account, click the code box dropdown and download a zip of the data directly to your computer.


## Rules

-   Any coding languages are allowed but all analyses must be reproducible by the panel.
-   All entries must be loaded into a public Github repo.
-   All entries must follow the submission formats outlined below.
-   All entries must include a max 1000 word report to accompany the forecast analyses. This can be as a separate PDF/hmtl or incorporated into a quarto/jupyter notebook.
-   All submissions must be complete by 14th December 2026


## How to Win!

Contest participants are required to develop a modelling algorithm to forecast species occurrence within a target UK region in 2026 for 9 species. Species target regions are summarised in a table below. An example modelling pipeline is provided in the repository to guide development. An example report and submission template has also been provided. 

| Species                     | Region     |
| --------------------------- | ---------- |
| `Euplagia_quadripunctaria`  | South East |
| `Fratercula_arctica`        | South East |
| `Haliaeetus_albicilla`      | South East |
| `Lutra_lutra`               | South East |
| `Pandion_haliaetus`         | Scotland   |
| `Pipistrellus_pipistrellus` | South East |
| `Sciurus_vulgaris`          | South East |
| `Triturus_cristatus`        | South East |
| `Vipera_berus`              | South East |


2 prizes will be given for the best and second best model at forecasting probability of species occurrence in a given target region for 2026. Please calculate and report the binomial deviance for each of the nine species individually, as well as the mean binomial deviance across all nine species. Binomial deviance should be calculated across the 5km grid cells for a given species. Treat each species equally when calculating the aggregate statistics.

The winners will be selected by the SPHERE-PPL Team and will be invited to present their forecasts at the next Annual Meeting. The SPHERE-PPL Team reserve the right to award a prize for a model that performs particularly well for one species. 

## How to Submit

If you forked the repo, congratulations, you have almost entered the contest! Make sure to update your repo with your results! Forecasts and reports should be saved into the submission folder, matching the template found within. We will run the [Forecast AggregatoR](https://github.com/SPHERE-PPL/Forecast-AggregatoR) the day following the close of the contest and your repo will be collated with the entries.

If you did not fork the repo, please send an email to [info\@sphere-ppl.org](mailto:info@sphere-ppl.org) with a link to your public github repo where your forecast and report are stored. These will then be collated with the other entries.

Please raise any questions or matters of clarification on the aforementioned GitHub page as an ‘issue’. These will be answered and all competitors will be able to see the response.


## Connect with the Community

You can join our Zulip [here](https://sphereppl.zulipchat.com/join/olwtpi7g3wbyh5mxv4uwipaw/) and check out our events page to see the next online catch-up.


## License

![CC-BYNCSA-4](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

Unless otherwise noted, the content in this repository is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
