# SciData2024_SMRFR
Paper code for "Global Multilayer Soil Moisture Dataset with Spatiotemporal Dynamic Insights Using Machine Learning Technique", submitted.

```
Email: yuhanliu@whu.edu.cn
```
### Abstract
Accurate and continuous monitoring of soil moisture (SM) is crucial for a wide range of applications, including agriculture, hydrology, and climate modelling. In this study, we present a novel machine learning based framework for generating a continuously updated, multilayer global SM dataset, and we generated SMRFR (Soil Moisture from Random Forests Regression algorithms) based on it. Utilizing publicly available reanalysis and remote sensing data in generation, SMRFR provides daily SM estimates at five soil layers (0-100 cm) with a fine spatial resolution of 9 km over the period 2000 to 2023. The evaluation results demonstrate SMRFR's potential to capture the spatial and temporal variability of SM. ML exhibits robust performance in transferring knowledge across continents in capturing transient and seasonal SM dynamics after rainfall events. Our novel SM dataset offers basis and scientific reference for research in agriculture, hydrology, and ecology.

Machine learning based model to generate SMRFR, Conda environment can be created from SMRFR_ml.yml
```
$ conda env create -f SMRFR_ml.yml
```
