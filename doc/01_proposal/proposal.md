# Proposal Foot & Bike Traffic in Zurich

## What questions will we try to answer with the project?
1. How does weather affect foot and bike traffic in Zurich City?
2. How many city bikes would need to be provided depending on weather condition and season (or month)?

## What data will be used
### Traffic Data - City of Zurich
**Data** *(Source)*: [Daten der automatischen Fussgänger- und Velozählung - Viertelstundenwerte](https://data.stadt-zuerich.ch/dataset/ted_taz_verkehrszaehlungen_werte_fussgaenger_velo)


More readings about how this data collection is beeing conducted: <br>
[Automatische Zählungen des Fussverkehrs ](https://www.stadt-zuerich.ch/ted/de/index/taz/verkehr/webartikel/webartikel_fussverkehrszaehlung.html) <br>
[Automatische Zählungen des Veloverkehrs](https://www.stadt-zuerich.ch/ted/de/index/taz/verkehr/webartikel/webartikel_velozaehlungen.html)

### Weather Data - City of Zurich
- https://opendata.swiss/en/dataset/stundlich-aktualisierte-meteodaten-seit-1992

### Population Data - City of Zurich
- https://opendata.swiss/de/dataset/bevolkerung-seit-1901


## What techniques will be used?

- Correlation-analysis
- Lasso Regression for variable selection and variable analysis
- Exploratory analysis
- Visualization of geo data (if possible)
- Regression models for prediction of traffic (GLM, ...)