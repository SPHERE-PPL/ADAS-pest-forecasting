# SPHERE-PPL Forecasting Contest – Wheat Crop Disease Forecasting


## Introduction

Zymoseptoria tritici infection, the causal agent of Septoria tritici blotch (STB), is the most economically damaging foliar disease of winter wheat in the UK. It is estimated to cost the industry around £300 million annually through yield losses and fungicide expenditure. Compounding the issue, the pathogen is increasingly developing resistance to available fungicides. 

STB reduces green leaf area, limiting photosynthesis and ultimately lowering both yield and grain quality. In severe cases, losses can reach up to 50%. 

The aim of this contest is to develop a model capable of forecasting the incidence and severity of Zymoseptoria tritici on wheat crop across UK regions for 2026, enabling farmers and stakeholders to take pre-emptive action to mitigate its impact.


## Data

The target outcome variable comprises annual measurements of disease severity and crop incidence of Zymoseptoria tritici on wheat leaves 1 and 2 across regions of the UK. These outcome data are sourced from the ADAS Crop Pest and Disease Survey.

Participants are encouraged to source, curate, and integrate relevant external explanatory datasets to improve predictive performance. Potential starting points may include variables such as:

[ADAS Agronomic Data](https://www.pestanddiseasesurvey.co.uk/the-database)

[COPERNICUS Bioclimate Data](https://cds.climate.copernicus.eu/datasets/sis-biodiversity-cmip5-global?tab=overview)

[DEFRA Pesticide Usage Data]( https://pusstats.fera.co.uk/home)

[LUH2 Land Use Data]( https://luh.umd.edu/index.shtml)


## Joining the contest & Getting Started

In order to join the contest, you will need to fork or download the repo.

To fork the repo, simply press the "fork" button, which can be found at the top of this github page. A step-by-step guide can be found [here](https://scribehow.com/shared/Forking_a_SPHERE-PPL_Forecasting_Contest_Repository_on_GitHub__o_bLCyQlTsO0o5YCmGsk8Q).

To download the data without a github account, click the code box dropdown and download a zip of the data directly to your computer.


## Rules

-   Any coding languages are allowed but all analyses must be reproducible by the panel.
-   All entries must be loaded into a public Github repo.
-   All entries must follow the submission formats outlined below.
-   All entries must include a max 1000 word report to accompany the forecast analyses. This can be as a separate PDF/hmtl or incorporated into a quarto/jupyter notebook.
-   All submissions must be complete by [DEADLINE]


## How to Win!

Awards will be given across two categories:

1. The team with the closest forecast, as measured by Root Mean Squared Error.  

2. The team with the most interesting report.

The winners will be selected by the SPHERE-PPL Team and will be invited to present their forecasts at the next Annual Meeting, with travel covered by the project.


## How to Submit

If you forked the repo, congratulations, you have almost entered the contest! Make sure to update your repo with your results! Forecasts and reports should be saved into the submission folder, matching the template found within. We will run the [Forecast AggregatoR](https://github.com/SPHERE-PPL/Forecast-AggregatoR) the day following the close of the contest and your repo will be collated with the entries.

If you did not fork the repo, please send an email to [info\@sphere-ppl.org](mailto:info@sphere-ppl.org) with a link to your public github repo where your forecast and report are stored. These will then be collated with the other entries.

Please raise any questions or matters of clarification on the aforementioned GitHub page as an ‘issue’. These will be answered and all competitors will be able to see the response.


## Connect with the Community

You can join our Zulip [here](https://sphereppl.zulipchat.com/join/olwtpi7g3wbyh5mxv4uwipaw/) and check out our events page to see the next online catch-up.


## License

![CC-BYNCSA-4](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

Unless otherwise noted, the content in this repository is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

For the data sets in the *data/* folder, please see [*data/README.md*](data/README.md) for the applicable copyrights and licenses.
