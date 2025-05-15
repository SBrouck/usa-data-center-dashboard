U.S. Data Center Market Mapping (CBRE H2 2024)
Author: Sacha Brouck
Tool: Tableau 
Data sources: CBRE reports, FCC, EIA, DataCenterMap

Project Overview
This visualization presents a structured and geolocated overview of the U.S. data center market based on infrastructure capacity, development pipelines, and operator presence. It served as the contextual foundation for my master's thesis:

Optimizing sustainable data center site selection through geospatial analytics, machine learning, and multi-criteria decision modeling

This interactive map, built in Tableau, enables exploration by market type (primary vs. secondary), hyperscaler presence, installed capacity, vacancy, and total number of data centers by state.

Research Process and Limitations
Unlike proprietary platforms such as DataCenterMap.com, which do not provide structured open access or APIs, this project was developed through extensive manual research.

This included:

Analyzing all reports published in the CBRE North America Data Center Trends H2 2024, including:

Main summary report

18 detailed local market profiles, including:

Northern Virginia

Phoenix

Dallas-Fort Worth

Seattle

View all markets

Supplementing with open-source and government data, including:

FCC Broadband Map

EIA – U.S. Energy Information Administration

DataCenterMap – U.S. State Totals

Due to the lack of centralized raw data, every market's indicators were individually extracted and validated from narrative or visual report content.

Dataset Description
The final CSV file (cbre_data_centers_final_US_only.csv) includes:

18 U.S. regional markets, each labeled as "Primary" or "Secondary"

Installed and under-construction capacity (MW)

Absorption rate, vacancy, and pre-leased space

Presence of hyperscalers and major operators

Latitude and longitude (approximate, per market)

Total number of data centers per state (sourced from DataCenterMap)

This dataset was formatted and merged manually in order to produce a clean input for Tableau.

Tableau Public Visualization
→ View the interactive Tableau dashboard here (insert your link)

The dashboard allows for:

Filtering by market type and operator presence

Comparing capacity vs. saturation

Exploring infrastructure development across geographies

Two screenshots are included in this repository:

Preview of the map

Preview of the structured dataset

Academic Context
This visualization was used as the geographic foundation for my thesis research on sustainable data center site selection. While the Tableau map focuses on infrastructure context, the full research goes further, incorporating:

Environmental cooling constraints

Energy source typologies

MCDM (multi-criteria decision models)

Predictive models for ranking potential sites

Reusability
The dataset and visual framework are open for adaptation.
Suggestions for extension include:

Adding ESG and climate risk metrics

Integrating fiber and network latency data

Building dashboards for individual state-level comparisons

Attribution is appreciated if reused.
