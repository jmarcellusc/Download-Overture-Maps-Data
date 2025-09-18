# Overture Map Data Downloader

This is a command-line executable that allows you to download geographical data from the [Overture Maps Foundation](https://overturemaps.org/). Overture Maps is a collaborative effort to create a reliable, easy-to-use, and openly available map dataset.

[Download Tool](https://www.dropbox.com/scl/fi/kmg4egsrpmhf5ohj3j8y9/Download-GIS-Data-v1.zip?rlkey=gawhonv5kf9l6k639okplgfdd&st=h8pd1iwd&dl=0)

## Features

* **Direct Download:** Fetches data directly from Overture Maps' public datasets.

* **Customizable Queries:** Allows you to specify the type of data you want to download (e.g., buildings, roads, parks).

* **Attribution-Compliant:** Automatically includes the necessary attribution for the Overture Maps Foundation in downloaded data metadata.

## Overture Maps Attribution

This executable uses data from the Overture Maps Foundation. All users of the data must adhere to their attribution requirements.

The Overture Maps Foundation requires the following attribution:

> Map data from Overture Maps Foundation, licensed under the Linux Foundation's [Community Data License Agreement – Permissive, Version 2.0 (CDLA-Permissive-2.0)](https://www.google.com/search?q=https://overturemaps.org/licensing/cdla-permissive-2-0/).

For more detailed information on attribution requirements, please refer to the official Overture Maps Foundation attribution policy documentation: <https://docs.overturemaps.org/attribution/>

## Getting Started

Instructions for this execuatable:
 - !! Requires OvertureMaps be installed and PATH updated
 - Requried Parameters
     - Project Name <string>
     - Bounding Coordinates 'min_long, min_lat, max_long, max_lat' <string> (can be aquired via http://bboxfinder.com/, make rectangle, copy box coords)
     - Select Data Type: <Numeric Selection>
    
## Citation

All methodlogy and data is from Overture Maps: 'Overture Maps Foundation, overturemaps.org'. Within their Attribution and Licensing, they state that data sourcs required thier own attribution and is found within a field of the data. 

[Overture Maps Attribution and Licensing](https://docs.overturemaps.org/attribution/)

Data used in this project is sourced from the Overture Maps Foundation ([https://overturemaps.org/](https://overturemaps.org/)).
