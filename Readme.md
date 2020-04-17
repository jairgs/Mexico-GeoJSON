This repository aims to store in GeoJSON different geographies of Mexico, particularly the political divisions. As such, this repository will add new GeoJSON files in the future. 

## Municipalities
There are 2 files of the municipality divisions:
- `municip.zip` with `municip.json` inside which contains the geographies as published by the official authorities (INEGI)
- `municip_simplified.json` with a simplified geography done with a .01 tolerance using the [shapely package](https://shapely.readthedocs.io/en/latest/manual.html)

I added the centroid for each Municipality inside the 'centroid' field of the GeoJSON.