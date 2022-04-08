### data_live_ref.csv AND data_sterile_ref.csv

These two files contain performance data of plant species where growth on live field-collected soil and on sterile soil serves the reference, respectively.
 
Variable descriptions:

- Experiment: unique number for each experiment included in the dataset. For expeirments included in Crawford et al.(2019)'s metadataset (experiment number 1-142), we kept the same experiment number. We numbered experiments from newly-included studies starting 143. 
- Study: unique number for each study included in the dataset. For studies included in Crawford et al.(2019)'s metadataset (study number 1-290), we kept the same study number. We numbered newer studies starting 291. 
- Species A: genus and species name (separated by underscore) of one of the plant species ("A") in the pairwise comparison
- Species B: genus and species name (separated by underscore) of the other species ("B") in the pairwise comparison
- species_pair: genus and species name of the two species (separated by underscore) in the pairwise comparison
- Fraction inoculum: fraction of soil inoculum (reference soil, conspecific cultivated soil, or heterospecific cultivated soil; as opposed to the sterile background soil) used in the second ("testing", or "response") phase
- Training environment: the environment where the training (or conditioning) phase took place
	- Lab: the training phase was conducted, or partially conducted in a lab, greenhouse, or growth chamber. Note that we re-classified the "LabField" category in Crawford et al. 2019 as "Lab".
	- Field: the training phase was exclusively conducted in the field or experimental garden. 
- Testing environment: the environment where the testing (or response) phase took place
	- Lab: the testing phase was conducted in a lab, greenhouse, or growth chamber. 
	- Field: the testing phase was conducted in the field or experimental garden. 
- Testing community: growth setting for the testing/response phase 
	- Individual: the testing species was grown individually without any neighbors
	- Population: the testing species was grown with conspecific neighbors
	- Community: the testing species was grown with heterospecific neighbors
- XinX mean: mean growth of species X ("A" or "B") in soil X ("A", "B", or "R" for reference)
- XinX se: standard error of mean growth of species X ("A" or "B") in soil X ("A", "B", or "R" for reference)
- XinX N: sample size of mean growth of species X ("A" or "B") in soil X ("A", "B", or "R" for reference)
- author: author information of the original study where data is sourced
- year: year of the original study where data is sourced
- who_entered: name of the author who extracted and entered the data, or part of the data (e.g. growth on reference soil for studies included in Crawford et al. 2019)
- study_control_type: all types of reference soil (separated by underscore) included in this study. Note that one study may include multiple reference choices for different pairwise comparisons:
	- FL: field-collected live soil
	- FS: sterilized field-collected soil
	- GS: sterilized greenhouse soil or potting mix
	- CS: averaged growth on various soil that was cultivated by each focal species and then sterilized
	- CmS: growth on soil that was cultivated by each focal species, pooled and homogenized, and then sterilized
- control_type: type of reference soil used in this pairwise comparison:
	- FL: field-collected live soil
	- FS: sterilized field-collected soil
	- GS: sterilized greenhouse soil or potting mix
	- CS: averaged growth on various soil that was cultivated by each focal species and then sterilized
	- CmS: growth on soil that was cultivated by each focal species, pooled and homogenized, and then sterilized
- Study_sterilization_method: the sterilization method of the sterile reference soil
	- NA: this variable is not applicable to data_live_ref.csv
	- gamma irradiation
	- autoclaving
	- heating
	- pasteurization, steam-pasteurization, steaming, and "not specified" (when the original study did not report their soil sterilization method) are all categoried as "other" in the analysis



### data_reference.csv

This file gives the full reference to each original study where the data came from.

Variable descriptions:
- Reference source: whether this study was included in the meta-dataset compiled by Crawford et al. (2019), or was resulted from the Web of Science search we conducted in July 2021 (keyword and details see maintext).  
- Study: unique number for each study as in 'data_live_ref.csv' and 'data_sterile_ref.csv'.
- Full Reference: full reference to the original study



### crawford-yan-extractions.csv

This file contains original data extracted by Crawford et al. (2019), with part of them re-extracted by Yan et al. using WebPlotDigitizer to confirm the consistency of data extraction. Columns with the "_reestimate" suffix contain the re-extracted data. All other columns have the original data compiled by Crawford et al. Column variable descriptions are the same as those for 'data_live_ref.csv' and 'data_sterile_ref.csv'.  

