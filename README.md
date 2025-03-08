# Mortality_and_AirPollution

## Project Overview
This project analyzes the relationship between various environmental and demographic factors and mortality rates using regression models in R. The dataset includes variables such as pollution levels, temperature, and socioeconomic factors.

## Dataset
The dataset included in `pollution.RData` refers to a study about the relationship between mortality in 60 US areas and air pollution. Some environmental and demographic information are collected:

- **mortality**: mortality rate (annual deaths for 100,000 persons)
- **precipitation**: mean annual precipitation (inches)
- **humidity**: percent relative humidity
- **Jan.temp**: mean January temperature (Fahrenheit)
- **July.temp**: mean July temperature (Fahrenheit)
- **over65**: percentage of the population aged 65 years or over
- **house**: population per household
- **education**: median number of school years completed for persons 25 years or older
- **comfort**: percentage of the housing that is sound with all facilities
- **density**: population density (in persons per square mile)
- **office**: percentage of office workers
- **poor**: percentage of households with annual income under 3,000 dollars
- **HC**: level of hydrocarbons
- **NOX**: dangerous level of oxides of nitrogen? (Yes: > 30 g/m³, No: ≤ 30 g/m³)
- **SO2**: dangerous level of sulfur dioxide? (Yes: > 125 g/m³, No: ≤ 125 g/m³)

## Results
- Mortality rates are influenced by precipitation, temperature, pollution, and socioeconomic factors.
- Higher pollution levels (SO₂) and poverty rates are associated with increased mortality.
- Higher temperatures in January and July tend to decrease mortality rates.
