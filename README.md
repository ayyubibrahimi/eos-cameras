# Data and analysis of surveillance cameras in New Orleans


## Data
- New Orleans Cameras: Source RTCC using script below
- Calls for Service (911 calls): Source data.nola.gov
- Police Reports: Source data.nola.gov
- Dataset on requests for surveillance data submitted to the Real Time Crime Center (RTCC) by the New Orleans Police Department (NOPD): Source - Data received from Public Records Requests/FOIAs submitted to NOPD. PRRs/FOIAs can be found in the `prrs` folder. 


## Downloading camera location data

The City of New Orleans releases camera locations as a [map without option to download](https://nolagis.maps.arcgis.com/apps/webappviewer/index.html?id=47ce86e8b9ec4d119d9eda5659d28a3e). This repository contains an HTML page that uses the ArcGIS JS library to gather the data from source and convert into a CSV.

- Open `camera-locations-download.html` in your browser
- Click the download button
- Ignore other texts and links on the page, it is from a page that is no longer maintained.