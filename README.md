# ParkMapSense: A Model for Parking Occupancy Mapping and Prediction in Smart Cities

## Authors

**Carlos Eduardo Liedtke Borges**¹, **Jorge Arthur Schneider Aranda**², **Jorge Luis Victória Barbosa**¹

¹ Applied Computing Graduate Program (PPGCA), University of Vale do Rio dos Sinos (UNISINOS), São Leopoldo, Rio Grande do Sul, Brazil.

² Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Sul (IFRS) – Campus Veranópolis, Rio Grande do Sul, Brazil.

## About

This repository is the official companion to the paper **"ParkMapSense: A Model for Parking Occupancy Mapping and Prediction in Smart Cities"**.

<!-- , submitted to the *Journal of Ambient Intelligence and Smart Environments* -->
<!-- Add the link when available -->

## Abstract

Urban mobility challenges have intensified with the rapid expansion of private vehicle fleets. To mitigate parking scarcity in central areas, municipalities often implement Metered Parking Zones to encourage vehicle turnover. These digitized systems generate historical data following the Arrive-Stay-Leave (ASL) pattern, enabling occupancy mapping and predictive analysis. This study introduces ParkMapSense, a computational model designed to generate occupancy maps and forecast parking availability. The model was validated using operational data from Novo Hamburgo, RS (Brazil), covering November 2022 to May 2024, comprising 1.4 million inspections and 1.3 million parking activations across 2,052 parking spaces. Occupancy was aggregated into 10-minute intervals, and prediction algorithms based on Global, 7-day, and 28-day moving averages were applied, segmented by weather conditions and day type. Rainfall data were integrated to analyze behavioral variations. Evaluation metrics showed R²Scores of 0.86 for weekdays without rain, 0.74 with rain, and 0.81 on Saturdays in any weather, confirming the model's ability to capture temporal patterns. The primary contribution lies in the occupancy mapping algorithm, which transforms metered parking data into structured time-series occupancy maps, and in the weather-aware segmentation strategy, which serve as lightweight baselines within an extensible structure designed to support future integration of other prediction algorithms. ParkMapSense demonstrated low computational cost and operational feasibility for medium-sized cities, offering valuable insights for urban mobility planning and enforcement optimization.

## Data and Code Availability

Neither the source code nor the operational dataset used in this study are publicly available at this time. Once authorization is granted and privacy concerns are resolved, this repository will be updated with:

- **Source code** of the ParkMapSense model
- **Operational dataset** (or references to an official open data portal)
- **Supplementary materials** to support reproducibility

In the meantime, the manuscript provides detailed algorithmic descriptions, pseudocode, database schema, and comprehensive documentation of model parameters and processing logic to enable independent reimplementation.

## Contact

For questions or collaboration inquiries, please contact: carlos.e.l.borges@gmail.com
