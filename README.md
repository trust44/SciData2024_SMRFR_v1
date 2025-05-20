# SciData2024_SMRFR
Paper code for "*SMRFR: A global multilayer soil moisture dataset using Random Forest with multi-source data*", submitted.

```
Email: yuhanliu@whu.edu.cn
```

SMRFR is a ML-based datasets generated using publicly available reanalysis and remote sensing data, which provides daily SM estimates at five soil layers (e.g., 0-5, 5-10, 10-30, 30-50 and 50-100 cm) with a 9-km spatial resolution from 2000 to 2023. SMRFR exhibits robust performance in transferring knowledge across continents, capturing transient and seasonal SM dynamics after rainfall events. SMRFR achieved an unbiased root mean square error of 0.0339 $m^{3}/m^{3}$ on the validation set. Our novel SM dataset offers a basis and valuable reference for agricultural, hydrological, and ecological research, enabling improved analysis and modelling of SM dynamics at regional to global scales.

Machine learning based model to generate SMRFR, Conda environment can be created from SMRFR_ml.yml
```
$ conda env create -f SMRFR_ml.yml
```
python scripts in ipynb format to create Figures
- Figure2.ipynb: Fig. 2
- Figure3.ipynb: Fig. 3
- Figure8&FigureS4.ipynb: Fig. 8/Fig. S4
