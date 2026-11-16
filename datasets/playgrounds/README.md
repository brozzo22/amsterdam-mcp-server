# Playgrounds and outdoor sports areas in Amsterdam

1,721 public play and sports locations managed by the city of Amsterdam (playgrounds, sports areas and combined sites), with the kinds of equipment the city lists at each one, its neighbourhood and district, and area in square metres where the city gives it. A copy of the Gemeente Amsterdam "Sport" open dataset, reshaped into one row per location. The city publishes it as open public data and requires no authorisation to use it. Not endorsed by Gemeente Amsterdam. Live map: https://essentiallyamsterdam.com/tools/amsterdam-playgrounds-map/

## Columns of data.csv (1,721 rows)
| Column | Meaning |
|---|---|
| id | City identifier of the location |
| name | Name or address of the location as the city gives it |
| latitude, longitude | WGS84 coordinates |
| kind | Playground; Playground and sports area; Sports area; Playground run by an association; Play or sports area (equipment not typed by the city) |
| equipment_types | Kinds of equipment the city lists at the location, separated by "; " (Swings, Slides, Climbing frames, Sand play, Water play equipment, Seesaws and spring riders, Roundabouts and spinners, Zip lines, Football and goals, Basketball, Table tennis, Skating, Outdoor fitness, Jeu de boules, Tennis, Volleyball); empty where none are typed |
| neighbourhood | Buurt (neighbourhood) |
| district | Stadsdeel (district) |
| area_m2 | Area in square metres where the city gives it; empty otherwise |

Rows per kind: Playground 975, Playground and sports area 454, Sports area 199, Play or sports area (equipment not typed by the city) 83, Playground run by an association 10.

## Source and licence
- Source: Gemeente Amsterdam, Sport dataset (v2), https://api.data.amsterdam.nl/v1/docs/datasets/sport@v2.html. The city's documentation marks the dataset as public ("Licentie: public", "Geen; dit is openbare data").
- No separate licence text is attached to the dataset. Please credit "Gemeente Amsterdam, compiled by Essentially Amsterdam" and link to https://essentiallyamsterdam.com/tools/amsterdam-playgrounds-map/.
- Data collected: 2026-11-16. Updated daily on the live map.

Published by Essentially Amsterdam (https://essentiallyamsterdam.com/).
