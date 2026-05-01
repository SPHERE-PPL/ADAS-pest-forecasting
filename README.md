# SPHERE-PPL Forecasting Contest – Wheat Crop Disease Forecasting


## Introduction

Zymoseptoria tritici, the causal agent of Septoria tritici blotch (STB), is widely regarded as the most economically important foliar disease of winter wheat in the UK. It is estimated to cost the industry on the order of £150–250 million annually through yield losses and fungicide inputs [(Harrison et al., 2024)](https://pmc.ncbi.nlm.nih.gov/articles/PMC11716361/?utm_source=chatgpt.com). Compounding this, the pathogen has shown a strong capacity to develop resistance to multiple fungicide classes [(Birr et al., 2021)](https://www.mdpi.com/2077-0472/11/3/269?utm_source=chatgpt.com).

Alongside STB, yellow rust caused by Puccinia striiformis represents another major threat to UK wheat production [(Chen et al., 2014)](https://pmc.ncbi.nlm.nih.gov/articles/PMC6638732/?utm_source=chatgpt.com). The disease spreads rapidly under cool, moist conditions and is characterised by yellow pustules on leaf surfaces, reducing photosynthetically active area. 

Both diseases reduce green leaf area, limiting photosynthesis and ultimately lowering yield and grain quality. In severe epidemics, yield losses can exceed 50% in susceptible, untreated crops [(Birr et al., 2021)](https://www.mdpi.com/2077-0472/11/3/269?utm_source=chatgpt.com).

The aim of this contest is to develop a model capable of forecasting the incidence and severity of these key wheat diseases across UK regions for 2026, enabling pre-emptive management decisions.


## Data

The target outcome variable (data/agronomic_data.csv) comprises annual measurements of disease severity and crop incidence of Zymoseptoria tritici and Yellow rust on wheat leaves 1 and 2 across regions of the UK. These outcome data are sourced from the [ADAS Crop Pest and Disease Survey](https://www.pestanddiseasesurvey.co.uk/).

Once algorithms are submitted the data for the assessment period of 2026 will be released. In the current development dataset, this period is represented by dummy values (-9999).

Participants are encouraged to source, curate, and integrate relevant external explanatory datasets to improve predictive performance. The repository includes several potential starting points including:

[ADAS Agronomic Data](https://www.pestanddiseasesurvey.co.uk/the-database) (data/agronomic_data.csv)

[COPERNICUS Bioclimate Data](https://cds.climate.copernicus.eu/datasets/sis-biodiversity-cmip5-global?tab=overview) (data/bioclim_data.csv)

[DEFRA Pesticide Usage Data]( https://pusstats.fera.co.uk/home) (data/fungicide_data.csv)

[LUH2 Land Use Data]( https://luh.umd.edu/index.shtml) (data/prop_LUC.csv)


## Joining the contest & Getting Started

In order to join the contest, you will need to fork or download the repo.

To fork the repo, simply press the "fork" button, which can be found at the top of this github page. A step-by-step guide can be found [here](https://scribehow.com/shared/Forking_a_SPHERE-PPL_Forecasting_Contest_Repository_on_GitHub__o_bLCyQlTsO0o5YCmGsk8Q).

To download the data without a github account, click the code box dropdown and download a zip of the data directly to your computer.


## Rules

-   Any coding languages are allowed but all analyses must be reproducible by the panel.
-   All entries must be loaded into a public Github repo.
-   All entries must follow the submission formats outlined below and in the example folder.
-   All entries must include a max 1000 word report to accompany the forecast analyses. This can be as a separate PDF/hmtl or incorporated into a quarto/jupyter notebook.
-   Participants must submit their final algorithms by 6 September 2026.
-   The assessment dataset will be released on the 14 September 2026, upon which competitors must apply their submitted algorithms in generating forecasts over the assessment period of 2026. 
-   The final deadline for participants to submit their forecasts is 28 September 2026. Final submissions will be compared with those made prior to the release of the assessment dataset to verify that the algorithms have remained consistent.


## How to Win!

Contest participants are required to develop a modelling algorithm to forecast the incidence and severity of both Zymoseptoria tritici and yellow rust on wheat leaves 1 and 2 across UK regions for the 2026 growing season. An example modelling pipeline is provided in the repository to guide development.

Target variables:

-   L1_Zymoseptoria_tritici_Disease_Severity
-   L1_Yellow_rust_Disease_Severity
-   L1_Zymoseptoria_tritici_Crop_Incidence
-   L1_Yellow_rust_Crop_Incidence
-   L2_Zymoseptoria_tritici_Disease_Severity
-   L2_Yellow_rust_Disease_Severity
-   L2_Zymoseptoria_tritici_Crop_Incidence
-   L2_Yellow_rust_Crop_Incidence

Awards will be given across three categories:

1. The team with the most accurate forecast of Zymoseptoria tritici, as measured by Root Mean Squared Error.  

2. The team with the most accurate forecast of Yellow rust, as measured by Root Mean Squared Error.  

3. The team with the most interesting report.

The winners will be selected by the SPHERE-PPL Team and will be invited to present their forecasts at the next Annual Meeting, with travel covered by the project.


## How to Submit

An example report and submission template has been provided.

If you forked the repo, congratulations, you have almost entered the contest! Make sure to update your repo with your results! Forecasts and reports should be saved into the submission folder, matching the template found within with your own forecasted values. We will run the [Forecast AggregatoR](https://github.com/SPHERE-PPL/Forecast-AggregatoR) the day following the close of the contest and your repo will be collated with the entries.

If you did not fork the repo, please send an email to [info\@sphere-ppl.org](mailto:info@sphere-ppl.org) with a link to your public github repo where your forecast and report are stored. These will then be collated with the other entries.

Please raise any questions or matters of clarification on the aforementioned GitHub page as an ‘issue’. These will be answered and all competitors will be able to see the response.


## Connect with the Community

You can join our Zulip [here](https://sphereppl.zulipchat.com/join/olwtpi7g3wbyh5mxv4uwipaw/) and check out our events page to see the next online catch-up.


## License

![CC-BYNCSA-4](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

Unless otherwise noted, the content in this repository is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

For the data sets in the *data/* folder, please see [*data/README.md*](data/README.md) for the applicable copyrights and licenses.
