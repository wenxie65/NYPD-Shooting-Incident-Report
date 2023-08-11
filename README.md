# NYPD Shooting Incident Report
This repository contains an analysis of shooting incident data obtained from the NYPD Shooting Incident Data (Historic) dataset. The primary objective of this analysis is to analyze shooting incident data and understand its trends. The analysis is conducted using the R programming language.

## Dataset
The dataset is sourced from the [NYPD Shooting Incident Data (Historic)](https://catalog.data.gov/dataset/nypd-shooting-incident-data-historic) available on Data.gov. This dataset provides information about shooting incidents in New York City.

## Data Preprocessing
In this project, missing values in the dataset were addressed by replacing them with "UNKNOWN." This approach ensures that the analysis maintains its accuracy while accounting for incomplete information.

## Analysis
Several visualizations were generated to explore shooting incident trends:
1. A plot illustrating shooting incidents across New York City demonstrates an initial gradual decline until around January 2020, followed by a significant upward trend. This suggests a potential shift in shooting incident patterns.
2. A similar trend is observed in Queens, with a decrease preceding January 2020, followed by an increase. This aligns with the overall trend in New York City.
3. Shooting incidents within Manhattan also show a trend resembling the one of Queens. However, the data summary indicates a lower incident count.
4. There's a big increase around January 2020 when we look at the data for the entire city or each borough separately. But a model that predicts trends using straight lines shows that the incidents were actually decreasing, possibly due to the decreasing trend before January 2020. The COVID-19 pandemic might have influenced the data, which could affect the number of shooting incidents.
