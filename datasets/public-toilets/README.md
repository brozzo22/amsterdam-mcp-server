# Public toilets in Amsterdam: locations, hours and prices

Location, type, opening days and hours, price per use and city district of 109 public toilets and urinals listed by the city of Amsterdam (dataset "Openbare toiletten", held by Verkeer en Openbare Ruimte). Entries in the city file without coordinates are left out (2 of 111). The original dataset is available free of charge from Gemeente Amsterdam under its Maps Data terms of use (https://maps.amsterdam.nl/open_geodata/terms.php), which also apply to this copy. The terms allow use and reuse for any lawful purpose, commercial included. This copy is not endorsed by Gemeente Amsterdam. Live map: https://essentiallyamsterdam.com/tools/public-toilets-amsterdam-map/

## Columns of data.csv (109 rows)
| Column | Meaning |
|---|---|
| id | Row number in this file |
| latitude, longitude | WGS84 coordinates |
| type | Type of toilet or urinal as named by the city |
| location_description | Where it is, as described by the city |
| district | Amsterdam district (stadsdeel), looked up from the city's gebieden API |
| price_per_use | Price per use as listed by the city (0 means free) |
| opening_days | Opening days where the city lists them |
| opening_hours | Opening hours as listed by the city |
| open_24_hours | yes if the city lists the location as open 24 hours |

## Source and licence
- Source: Gemeente Amsterdam, Maps Data: Openbare toiletten (bronhouder Verkeer en Openbare Ruimte), https://maps.amsterdam.nl/open_geodata/?k=240
- Licence: Gemeente Amsterdam Maps Data Gebruiksvoorwaarden (free reuse for any lawful purpose, commercial included), https://maps.amsterdam.nl/open_geodata/terms.php. The original dataset is available free of charge from Gemeente Amsterdam under its Maps Data terms of use (https://maps.amsterdam.nl/open_geodata/terms.php), which also apply to this copy. The terms allow use and reuse for any lawful purpose, commercial included. This copy is not endorsed by Gemeente Amsterdam.
- Data collected: 2026-11-16. Opening times and prices are as the city lists them and can change.

Published by Essentially Amsterdam (https://essentiallyamsterdam.com/).
