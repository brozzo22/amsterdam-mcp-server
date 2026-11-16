# Registered bike and moped thefts per Amsterdam neighbourhood, 2024 and 2025

Police-registered thefts of bicycles, mopeds and light mopeds (police crime type 1.2.3, "Diefstal van brom-, snor-, fietsen") for every Amsterdam neighbourhood (wijk) in 2024 and 2025, with the district (stadsdeel) of each, the number of residents on 1 January 2025 and, where a neighbourhood has at least 1,000 residents, thefts per 1,000 residents in 2025. Both years are marked "Definitief" by the source. A second file gives the city-wide total per year and a third gives totals per district. Built from Politie table 47018NED and CBS Wijken en buurten 2025, both CC BY 4.0. Live interactive map and ranking: https://essentiallyamsterdam.com/tools/bike-theft-amsterdam-by-neighbourhood/

## Files
- `data.csv`: one row per neighbourhood (110 rows)
- `city_by_year.csv`: city-wide total per year (14 rows, 2012 to 2025)
- `districts.csv`: totals per district (9 rows)

## Columns of data.csv
| Column | Meaning |
|---|---|
| wijk_code | CBS neighbourhood (wijk) code |
| neighbourhood_wijk | Neighbourhood name |
| district_stadsdeel | Amsterdam district the neighbourhood belongs to |
| residents_1_jan_2025 | Residents on 1 January 2025 (CBS Kerncijfers wijken en buurten 2025) |
| thefts_2024 | Police-registered thefts of bicycles, mopeds and light mopeds in 2024 |
| thefts_2025 | The same count for 2025 |
| thefts_2025_per_1000_residents | thefts_2025 divided by residents, times 1,000; left empty where the neighbourhood has fewer than 1,000 residents |

## Source and licence
- Thefts: Politie, Geregistreerde misdrijven; soort misdrijf, wijk, buurt, jaarcijfers (CBS table 47018NED), https://data.politie.nl/#/Politie/nl/dataset/47018NED/table. Source last modified 2026-11-16.
- Residents: CBS Kerncijfers wijken en buurten 2025 (residents on 1 January 2025). Neighbourhood-to-district link: Gemeente Amsterdam, gebieden API (api.data.amsterdam.nl).
- Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Please credit "Politie / CBS, compiled by Essentially Amsterdam" and link to https://essentiallyamsterdam.com/tools/bike-theft-amsterdam-by-neighbourhood/.
- Data collected: 2026-11-16. Updated when the source publishes new figures.

Registered thefts are the cases reported to and recorded by the police; they are not a count of all thefts that happen.

Totals: the neighbourhood rows in data.csv add up to 13,272 thefts for 2025, while the city-wide figure in city_by_year.csv is 13,290. The difference is not assigned to any neighbourhood in this file.

Published by Essentially Amsterdam (https://essentiallyamsterdam.com/).
