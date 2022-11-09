# BMI Class Recognition from Respiratory Ausculation
The repository contains 3 notebooks:
```
|
|
|---Classification.ipynb
|---Processing the demographics.ipynb
|---Visualization.ipynb
|---
|
```
The data for the experiment have been obtained from [ICBHI 2017 Challenge](https://bhichallenge.med.auth.gr/ICBHI_2017_Challenge). The [demographics](https://bhichallenge.med.auth.gr/sites/default/files/ICBHI_final_database/ICBHI_Challenge_demographic_information.txt) data was obtained from a subset of the same dataset.

Firstly, the file `Processing the demographics.ipynb` contains details on how the sound data was transformed, filtered, processed, etc. Also mapping between the main dataset and demographics have been done in here. This also exports the data to `.csv` which have been further processed.

Secondly, the file `Visualization.ipynb` shows the visualization of the data was performed. All the graphs have been generated in here.

Finally, the file `Classification.ipynb` shows the classification performance for all different data types. Also, PCA and LDA have been compared here.

### Cite the code at:
```
@article{adhikary_ghosh_nandi_2022,
title={BMI Class Recognition from Respiratory Ausculation},
url={https://github.com/subhrangshu/lung-sound-bmi-classification/},
journal={GitHub},
author={Adhikary, Subhrangshu and Ghosh, Arindam and Nandi, Subrata},
year={2022},
doi={10.5281/zenodo.7306471},
month={Nov}} 
```


## References
Rocha BM et al. (2019) "An open access database for the evaluation of respiratory sound classification algorithms" Physiological Measurement 40 035001
