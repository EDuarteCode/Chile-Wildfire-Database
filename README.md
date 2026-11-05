# Wildfire data for Mediterranean Chile

This repository contains wildfire data supporting the manuscript *Wildfire Activity in Mediterranean Chile: Long-Term Burned-Area Dynamics, Ignition Causes, Initial Fuel, Burned Land Cover, and Municipal Fire Patterns* (PYRO-D-26-00029R1). The original data were provided by Chile’s Corporación Nacional Forestal (CONAF).

The data supporting this study are available in the following link: https://www.dropbox.com/scl/fi/234kgmvb0a0nkko65mn8u/wildfire-event-records-2002-2003-to-2025-2026.zip?rlkey=g5d7bskdb9d59btau2jbx5r5i&dl=0

## Which file should I use?

- `0. Consolidated-wildfire-database.xlsx` contains the English-language consolidated data used for the event-level analyses and pivot tables for key summaries. It covers 24 fire seasons, from 2002–2003 through 2025–2026.
- `0. Historical regional burned-area data 1977 - 2024` contains historical regional burned-area statistics, including the pre-2002 data used in the long-term analysis.
- `0. Municipal_burned_area_normalized_2002-2026` contains municipal burned-area summaries expressed relative to municipal area.
- `0. Removed_duplicate_records` documents the duplicate records excluded from the consolidated database.
- `1. Base Datos IIFF 2002-2003`, `2. Base Datos IIFF 2003-2004`, and subsequent numbered files are the CONAF source spreadsheets, with one file per fire season. Their names and headers are in Spanish. `IIFF` stands for *incendios forestales* (wildfires).

## Reading the data

The source spreadsheets retain CONAF’s Spanish field names. For example, `Superficie total Has` means **total burned area (ha)**. A fire season runs from 1 July through 30 June of the following year. A fire affecting more than one municipality may appear in separate municipality-level entries, so record counts and counts of distinct fires can differ.

See the manuscript and its Supplementary Materials for database selection, duplicate removal, analytical definitions, and the mapping from original CONAF ignition-cause labels to analytical categories.

## Column glossary

Use this glossary to interpret the column headers in the CONAF seasonal spreadsheets.

| Spreadsheet header | English label |
| --- | --- |
| `Temporada` | Fire season |
| `Region` | Region |
| `Province` | Province |
| `Municipality` | Municipality |
| `Name of the Fire` | Fire name |
| `Escenario` | Scenario |
| `Coord. operativas UTM E` | Operational UTM easting |
| `Coord. operativas UTM N` | Operational UTM northing |
| `Huso op.` | Operational UTM zone |
| `Coord. operativas Lat` | Operational latitude |
| `Coord. operativas Lon` | Operational longitude |
| `Combustible inicial` | Initial fuel |
| `Causa general` | General ignition cause |
| `Pino 0 a 10` | Pine plantations, ages 0–10 years |
| `Pino 11 a 17` | Pine plantations, ages 11–17 years |
| `Pino 18 o más` | Pine plantations, ages 18 years and older |
| `Eucalipto` | Eucalyptus plantations |
| `Otras plantaciones` | Other plantations |
| `Subtotal plantaciones` | Plantation subtotal |
| `Arbolado` | Tree cover |
| `Matorral` | Shrubland |
| `Pastizal` | Grassland |
| `Subtotal vegetación natural` | Natural vegetation subtotal |
| `Agrícola` | Agricultural land |
| `Desechos` | Waste and debris |
| `Subtotal otras superficies` | Other surfaces subtotal |
| `Superficie total Has` | Total burned area (ha) |
| `Inicio` | Fire start |
| `Detección` | Detection |
| `Aviso` | Notification |
| `Despacho` | Dispatch |
| `Salida` | Departure |
| `Arribo` | Arrival |
| `Primer ataque` | Initial attack |
| `Control` | Fire control |
| `Extinción` | Fire extinguishment |
| `Temperatura °C` | Temperature (°C) |
| `Humedad %` | Relative humidity (%) |
| `Exposición` | Slope aspect |
| `Dirección viento` | Wind direction |
| `Velocidad viento Km/hra` | Wind speed (km/h) |
| `Topografía` | Topography |
| `Pendiente` | Slope |
