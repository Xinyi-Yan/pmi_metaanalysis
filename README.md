# Plant-microbe-interaction (pmi) meta-analysis

This repository contains data and code for Yan et al. 'A quantitative synthesis of soil microbial effects on plant species coexistence'.

The data directory contains data used in the main and supplementary analyses. - 'data_live_ref.csv' contains performance data of plant species where growth on live field-collected soil serves the reference. 
- 'data_sterile_ref.csv' contains performance data of plant species where growth on multiple types of sterile soil serves the reference. 
- 'data_reference.csv' gives the full reference to each original study where the data came from. 
- 'crawford_yan_extractions.csv' contains original data extracted by Crawford et al. (2019), with part of them re-extracted by Yan et al. using WebPlotDigitizer to confirm the consistency of data extraction. 
- 'Data_README.txt' contains variable descriptions for each of the above four data files.

The code directory contains the 'analysis.RMD' with all analysis code, and the knitted 'analysis.html' -- an interactive webpage showing code and output. It also contains a 'saved_results' sub-folder, where some objects in the 'analysis.RMD' are saved to be loaded in the future, to avoid long waiting time when running the code. 

Please contact [Xinyi Yan](xinyiyan@utexas.edu) or [Gaurav Kandlikar](gaurav.kandlikar@gmail.com) to report issues.
