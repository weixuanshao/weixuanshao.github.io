---
title: "Literature Research"
excerpt: "Summary of key research papers related to cloudburst prediction"
collection: portfolio
---

### 1. High-Resolution Impact-Based Early Warning System for Riverine Floods

#### Full Citation:
Emerton, R., H. L. Cloke, E. Stephens, E. Zsoter, S. J. Woolnough, and F. Pappenberger, 2024: High-resolution impact-based early warning system for riverine floods. Nat. Commun., 15, 48065, https://doi.org/10.1038/s41467-024-48065-y.

#### Main Objective:
The study aims to develop a high-resolution, impact-based early warning system for riverine floods to enhance disaster preparedness and response.

#### Methods and Approaches:
The study combines meteorological forecasts, hydrological models (how water moves in rivers), and high-resolution hydrodynamic simulations (how floods spread) to improve flood prediction accuracy. Using a 10-meter spatial resolution, the system enables localized flood forecasting at the street and infrastructure level.

#### Key Findings and Results:
The system can predict maximum water levels 24 to 48 hours in advance, enabling timely flood warnings. High-resolution hydrodynamic modeling produces detailed flood inundation maps, identifying at-risk buildings and infrastructure. Its computational efficiency supports real-time operational use, allowing for rapid and accurate flood forecasting.

#### Performance Metrics Reported:
Lead Time for Warnings: The system predicts maximum water levels 24 to 48 hours before surpassing critical flood thresholds.
Computational Efficiency: At a 10-meter resolution, the system runs simulations 211 times faster than real-time events.

#### Data Sources and Features Used:
It uses weather models (ICON D2-EPS), hydrological models (mHM), flood simulation models (RIM2D), and geospatial data (OpenStreetMap) to improve reliability. The combination of historical data + real-time observations + model simulations strengthens prediction accuracy.

#### Limitations and Challenges Identified:
Many flood-prone areas lack high-resolution terrain, soil, and real-time meteorological data, reducing prediction accuracy. Also, high-resolution flood models require significant computational power, potentially delaying decision-making and emergency response.

#### Relevance to Our Project:
The paper’s multi-model approach provides a framework for integrating weather and geographic data to improve cloudburst prediction accuracy. Its 10-meter resolution modeling offers insights for localizing warnings, and its impact-based warning system serves as a model for making cloudburst alerts more actionable for emergency response.

### 2. Domino: A New Framework for Automated Identification of Weather Event Precursors

#### Full Citation:
Dorrington, J., C. Grams, F. Grazzini, L. Magnusson, and F. Vitart, 2023: Domino: A new framework for the automated identification of weather event precursors, demonstrated for European extreme rainfall. arXiv preprint, arXiv:2306.16787, https://doi.org/10.48550/arXiv.2306.16787.

#### Main Objective:
The study aims to develop an automated framework that identifies large-scale atmospheric precursors for extreme rainfall, allowing for earlier and more reliable weather warnings.

#### Methods and Approaches:
The study applies logistic regression models to analyze historical weather data and detect recurring atmospheric patterns that precede extreme rainfall. It focuses on large-scale circulation features, such as pressure and wind anomalies, to identify precursors 2 to 6 days in advance across different regions.

#### Key Findings and Results:
The system successfully identifies atmospheric precursors that signal extreme rainfall events several days in advance, extending the lead time compared to traditional short-term forecasts. However, precursor patterns vary by region and season, requiring localized adjustments. The framework demonstrates the potential of machine learning in improving early warning systems beyond immediate meteorological observations.

#### Performance Metrics Reported:
Prediction Lead Time: It identifies precursors 2 to 6 days before extreme rainfall.
Model Accuracy: Logistic regression models show statistically significant skill in detecting precursors, though performance varies by location and season.

#### Data Sources and Features Used:
The study uses historical atmospheric data to analyze pressure systems, wind anomalies, and large-scale circulation patterns. The dataset includes multiple European regions, providing a diverse test environment for validating precursor identification.

#### Limitations and Challenges Identified:
Precursor signals differ by region and season, requiring localized model adjustments. Also, uncertainty remains in linking identified precursors to specific rainfall intensities.

#### Relevance to Our Project:
The Domino framework enhances early warnings by identifying atmospheric precursors for extreme rainfall, improving cloudburst prediction lead times. Its machine learning approach boosts accuracy, complementing traditional methods. Additionally, its region-specific analysis supports customized models for better local forecasting.