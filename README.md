# Sofia's metro stations (a work in progress)

An effort to open-source a high-quality dataset of the shapes of Sofia's subway stations. This dataset is meant for the web app [ВелоСФ / velo-sofia.com](https://velo-sofia.com), but I would like to keep it open for all devs to use.
Opening one of the geojson files in GitHub's desktop app will show a preview. [Geojson.io](https://geojson.io/) will be the main tool used for edits.

<img width="1261" height="974" alt="An example of the precision of floor plans I'd like to achieve" src="https://github.com/user-attachments/assets/eeacdb7f-06f7-45f4-991c-6c46fa4503cb" />

## Possible sources

- [Sofiaplan's "Метростанции"](https://urbandata.sofia.bg/dataset/subway-stations)
  - [Open data](https://sofiaplan.bg/%D0%BF%D1%80%D0%B0%D0%B2%D0%B0-%D0%B7%D0%B0-%D0%BF%D0%BE%D0%BB%D0%B7%D0%B2%D0%B0%D0%BD%D0%B5-%D0%BD%D0%B0-%D0%BC%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D0%B8/)
  - Low-quality data (inaccurate and incomplete shapes)
  - No station names and meaningful attributes
- [Sofiaplan's "Метростанции - входове"](https://urbandata.sofia.bg/dataset/metro-stations-entrances)
  - [Open data](https://sofiaplan.bg/%D0%BF%D1%80%D0%B0%D0%B2%D0%B0-%D0%B7%D0%B0-%D0%BF%D0%BE%D0%BB%D0%B7%D0%B2%D0%B0%D0%BD%D0%B5-%D0%BD%D0%B0-%D0%BC%D0%B0%D1%82%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D0%B8/)
- Pictures of printed floor plans shown in the stations
  - I will upload them in this project sorted by metro line.
- [Easyway](https://www.eway.bg/bg/cities/sofia)
  - [Not considered open data](https://www.eway.bg/bg/api)
  - Very high-quality data
- [Planning documents for the subway network](https://gis.sofiaplan.bg/server/rest/services/transport)
  - Likely not considered open data
  - Already mostly included in Sofiaplan's open dataset
  - Links
    - [Метростанции от ОУП 2009 г.](https://gis.sofiaplan.bg/server/rest/services/transport/relsov_mget/FeatureServer/5)
    - [Метростанции от ИОУП 2017 г.](https://gis.sofiaplan.bg/server/rest/services/transport/relsov_mget/FeatureServer/0)
    - [Метростанции от ИОУП 2022 г.](https://gis.sofiaplan.bg/server/rest/services/transport/relsov_mget/FeatureServer/1)
- [Trinmo.org](https://map.trinmo.org/)
  - Already uses Easyway's data

