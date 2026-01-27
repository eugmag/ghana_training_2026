# UKCEH West Africa Hydrological Forecasting Training Workshop 2026
<p align="center">
  <img width="865" height="112" alt="image" src="https://github.com/eugmag/ghana_training_2026/blob/main/content/workshop_logo.png" />
</p>

Welcome to the repository for the UKCEH West Africa Hydrological Forecasting Training Workshop 27-29 January 2026.

This repository supports a three-day training workshop focused on building end-to-end capability in hydrological forecasting, from data access and exploration to modelling and operational forecast applications. The workshop progresses from working with hydroclimate datasets, through machine-learning-based water resources modelling, to the generation and interpretation of sub-seasonal to seasonal hydrological forecasts for decision making. The materials are organised by day and theme, with each section containing follow-along notebooks, scripts, example datasets, and guidance to enable participants to reproduce and adapt the methods introduced during the sessions.

---

## Training Objectives
The high-level objectives of this summer school are:
- Demonstrate how to access, retrieve, and work with remote hydrological and hydroclimate datasets using Python and common data access protocols.
- Introduce key hydrological and hydroclimate datasets and explore practical techniques for data processing, visualisation, and exploratory analysis.
- Provide hands-on experience with water resources modelling using machine-learning approaches, including feature engineering, model training, hyperparameter tuning, and model evaluation.
- Introduce conceptual hydrological modelling for catchment-scale applications and guide participants through model calibration and simulation.
- Demonstrate the generation and interpretation of sub-seasonal to seasonal hydrological forecasts, including ensemble streamflow prediction.
- Explore approaches for visualising, categorising, and communicating forecast products to support decision-making in operational contexts.

<a id='running-on-colab'></a>
## Running the Training Notebooks on Google Colab
To run the training notebooks using *Google Colab*, follow these steps:
1. **Log in to your Google account** and open [Google Colab](https://colab.research.google.com/).
2. In Colab, go to **File > Open notebook**.
3. Select the **GitHub** tab.
4. Paste the URL of the GitHub repository (NERC-CEH/ghana_hydro_training_2026) into the search bar.
5. You will get the list of the notebooks (ending in `.ipynb`) within the repository.
6. Click on the notebook you want to open.

> **Important:** Before you start editing, make sure to **Save a copy to your own Google Drive**.

7. Go to **File > Save a copy in Drive**. This will open a new tab with the title `Copy of <Notebook Name>`.
8. You are now working on your own copy of the notebook, which you can rename if you choose.
9. You can safely close the original (read-only) notebook tab and continue working on your personal copy.
10. The copied notebook will be saved in your Google Drive and can be accessed anytime.

---

## Introduction to the Workshops
This series of interactive, hands-on workshops is designed to introduce participants to practical approaches for hydrological forecasting and analysis. Each session focuses on a key component of the hydrological forecasting workflow, progressing from accessing and exploring hydrological and hydroclimate datasets, through data-driven and machine-learning-based water resources modelling, to the application of hydrological models for sub-seasonal to seasonal forecasting and decision-support. The workshops emphasise practical skill development through guided exercises, enabling participants to apply the methods and tools introduced to their own research and operational contexts.

### Overview Agenda
| | Day 1:  <br> 27 January 2026 <br> Theme: Hydrological Datasets | Day 2: <br> 28 January 2026 <br> Theme: Water Resources Modelling | Day 3: <br> 29 January 2026 <br> Theme: Seasonal Forecast Applications |
| --- | --- | --- | --- |
| 08:30 - 09:00 | **REGISTRATION** | --- | --- |
| 09:00 - 10:00 | Welcome & Introductions | **Talk:** Reservoir modelling <br> **Talk:** Introduction to Machine Learning (ML)   | **Talk:** Introduction to forecast methods & applications |
| 10:00 - 11:00 | **Hands-on:** Computing setup and testing | **Workshop:** ML reservoir modelling | **Workshop:** Running a hydrological model |
| 11:00 - 11:30 | **BREAK** | **BREAK** | **BREAK** |
| 11:30 - 13:00 | **Workshop:** Remote data access | **Workshop:** ML reservoir modelling | **Workshop:** Running Ensemble Streamflow Prediction (ESP) |
| 13:00 - 14:00 | **LUNCH** | **LUNCH** | **LUNCH** |
| 14:00 - 15:30 | **Workshop:** Data analysis and visualisation | **Talk:** the benefits of a multi-reservoir ML model <br> **Workshop:** ML reservoir modelling | **Talk:** WMO HydroSOS <br> **Workshop:** Categorising a forecast product for enhanced decision making |
| 15:30 - 16:00 | **BREAK** | **BREAK** | **BREAK** |
| 16:00 - 17:00 | Q/A and wrap-up | Group discussion on workshop outcomes <br> Q/A and wrap-up | Q/A, wrap-up and close |
| 18:00 - 21:00 | --- | **GROUP DINNER** | --- |


### Theme 1: Hydrological Datasets
**Facilitators:** *Eugene Magee | Amulya Chevuturi*

Follow-along session on accessing and retrieving remote hydrological datasets using Python, including common tools and protocols for working with data hosted on public or institutional servers. Hands-on session on exploring different types of hydroclimate datasets, including basic techniques for processing, visualisation, and analysis.

### Theme 2: Water Resource Modelling
**Facilitators:** *Helen Baron | Nathan Rickards*

An introduction to reservoir storage forecasting, with a hands-on application of machine learning using a tree-based data-driven approach. Data selection, feature engineering and selection, hyper parameter tuning and model evaluation will all be explored in the context of building a robust machine learning tool to help forecast reservoir storage at a monthly to seasonal timestep.


### Theme 3: Seasonal Forecast Applications
**Facilitators:** *Eugene Magee | Ezra Kitson | Lucy Barker*

This day provides R workbooks that introduce participants to running a lumped catchment hydrological model, using it to generate simple sub-seasonal to seasonal forecasts, and visualising forecast outputs. The first session introduces participants to the GR6J hydrological model, calibrating and running it with rainfall and potential evapotranspiration inputs. The second session then applies that calibrated model to "Ensemble Streamflow Prediction" forecasting, and the third session formats the forecast outputs into graphics suitable for decision making.

---

## Contact
If you have any questions or need assistance with the workshops, please feel free to get in touch with us:

> [National Capability for Global Challenges Team](mailto:NC-international@ceh.ac.uk)

> [UKCEH West Africa Office](westafrica@ceh.ac.uk)


---

## Acknowledgements
This workshop was supported by the Natural Environment Research Council as part of the NC-International programme delivering National Capability [NE/X006247/1]. 

## License 
© 2025 UK Centre for Ecology & Hydrology. This is an open-access repository under the terms of the Creative Commons Attribution License, which permits use, distribution, and reproduction in any medium, provided the original reporsitory is properly cited.

