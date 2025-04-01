# SciData2024_SMRFR
Paper code for "SMRFR: global multilayer soil moisture dataset with spatiotemporal dynamic insights using machine learning", submitted.

```
Email: yuhanliu@whu.edu.cn
```
### Abstract
Accurate and continuous monitoring of soil moisture (SM) is crucial for a wide range of applications in agriculture, hydrology, and climate modelling. In this study, we present a novel machine learning (ML) based framework for generating a continuously updated, multilayer global SM dataset, and we introduced SMRFR (e.g., Soil Moisture from Random Forest Regression). Utilizing publicly available reanalysis and remote sensing data for generation, SMRFR provides daily SM estimates at five soil layers (e.g., 0-5, 5-10, 10-30, 30-50 and 50-100 cm) with a fine spatial resolution of 9-km over the period 2000 to 2023. The evaluation results demonstrate SMRFR's potential to capture the spatial and temporal SM variability. SMRFR exhibits robust performance in transferring knowledge across continents, capturing transient and seasonal SM dynamics after rainfall events, with medium unbiased root mean square error of 0.0339 m^{3}/m^{3} evaluated with testing set. Our novel SM dataset offers basis and scientific reference for agricultural, hydrological, and ecological studies.

Machine learning based model to generate SMRFR, Conda environment can be created from SMRFR_ml.yml
```
$ conda env create -f SMRFR_ml.yml
```
