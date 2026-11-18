# CE 486/586 GIS Tutorials

Python notebooks for **CE 486/586 Geographic Information Systems**, The University of Alabama.
Click **Open in Colab** to run a notebook in your browser; all you need is a Google account.

| | |
|---|---|
| **Instructor** | Pushpendra Raghav |
| **Email** | ppushpendra@ua.edu |
| **Department** | Civil, Construction, and Environmental Engineering |
| **University** | The University of Alabama |

## Tutorials

| Lab | Tutorial | Open |
|---|---|---|
| 21–22 | **From a DEM to an IUH to GeoAI** (Carroll Creek, Tuscaloosa County): watershed, travel time and unit hydrograph with WhiteboxTools; water and wetland mapping with pretrained and self-trained AI (U-Net), with and without HAND. Use a T4 GPU. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/praghav444/CE486-586-GIS-Tutorials/blob/main/tutorials/hydrology_geoai/Lab21_22_IUH_GeoAI_Colab.ipynb) |
| Demo | **Earth Engine + AlphaEarth Foundations**: unsupervised clusters and similarity search with satellite embeddings. Needs an Earth Engine account and Cloud project. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/praghav444/CE486-586-GIS-Tutorials/blob/main/tutorials/demos/Lab22_EarthEngine_demo.ipynb) |

## Data

Downloaded by the notebooks: USGS 3DEP 10 m DEM, USGS Watershed Boundary Dataset, USDA NAIP aerial photos (Microsoft Planetary Computer), USFWS National Wetlands Inventory.

## Run locally

```bash
git clone https://github.com/praghav444/CE486-586-GIS-Tutorials.git
cd CE486-586-GIS-Tutorials
pip install -r requirements.txt
```

## License

[MIT](LICENSE)
