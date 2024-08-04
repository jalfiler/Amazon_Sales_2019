# Amazon Sales Data Analysis 2019

This repository contains an in-depth analysis of Amazon's technology product sales in urban ZIP codes during 2019. The project explores sales trends, popular products, and the influence of demographic factors using R and various data visualization techniques.

## Table of Contents

- [Project Overview](#project-overview)
- [Data](#data)
- [Installation](#installation)
- [Results](#results)
- [License](#license)
- [Disclaimer](#disclaimer)

## Project Overview

In this analysis, we explore the sales trends and patterns of Amazon's technology products across various urban ZIP codes in 2019. Our goal is to uncover key insights about consumer behavior and market dynamics in different urban areas.

## Data

- `sales_data.Rdata`: Amazon sales data of technology products placed over several months in 2019 in select urban ZIP codes.
- `zip_info.csv`: Demographic information for the ZIP codes included in the sales data.

## Installation

### Prerequisites

- R (version 4.0.0 or higher)
- RStudio
- Packages:

  - `tidyverse` (1.3.1)
  - `lubridate` (1.7.10)
  - `scales` (1.1.1)
  - `rio` (0.5.16)
  - `vtable` (1.3.0)
  - `kableExtra` (1.4.0)

## Results
The analysis reveals several key insights:

  - Sales of technology products show distinct daily and monthly trends, with significant spikes during holiday seasons.
  - Popular products like “USB-C Charging Cable” and “Bose SoundSport Headphones” drive a large portion of sales.
  - Higher sales volumes are observed in urban areas with higher median household incomes and larger populations.
  - Specific ZIP codes and cities stand out as major sales hubs, indicating targeted marketing opportunities.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer
The analysis presented in this document is based on the provided dataset and is intended for educational purposes only. Any conclusions drawn from this data should be considered in the context of the data's limitations. The data used in this analysis is publicly available and was obtained from Amazon. All efforts have been made to ensure the accuracy of the data, but no guarantees are provided.
