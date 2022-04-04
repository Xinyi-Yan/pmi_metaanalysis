### data_live_ref.csv

Variable descriptions:

- Experiment: unique number for each experiment included in the dataset. For expeirments included in Crawford et al.(2019)'s metadataset (experiment number 1-142), we kept their experiment number. We numbered experiments from newly-included studies starting 143. 
- Study: unique number for each study included in the dataset. For studies included in Crawford et al.(2019)'s metadataset (study number 1-290), we kept their study number. We numbered newer studies starting 291. 
- Species A: genus and species name (separated by underscore) of one of the plant species ("A") in the pairwise comparison
- Species B: genus and species name (separated by underscore) of the other species ("B") in the pairwise comparison
- species_pair: genus and species name of the two species (separated by underscore) in the pairwise comparison
- Fraction inoculum: fraction of soil inoculum (reference soil, conspecific cultivated soil, or heterospecific cultivated soil; as opposed to the sterile background soil) used in the second ("testing", or "response") phase
- Training environment:
- Testing environment:
- Testing community:
- XinX mean: mean growth of species X ("A" or "B") in soil X ("A", "B", or "R" for reference)
- XinX se: standard error of mean growth of species X ("A" or "B") in soil X ("A", "B", or "R" for reference)
- XinX N: sample size of mean growth of species X ("A" or "B") in soil X ("A", "B", or "R" for reference)
- author: author information of the original study where data is sourced
- year: year of the original study where data is sourced
- who_entered: name of the author who extracted and entered the data, or part of the data (e.g. growth on reference soil for studies included in Crawford et al. 2019)
- study_control: all type of reference soil (separated by underscore) included in this study. Note that one study may include multiple reference choices for different pairwise comparisons:
	- FL: field-collected live soil
	- FS: sterilized field soil
	- 
- control_type: type of reference soil used in this pairwise comparison. 
	- FL: field-collected live soil
- Study_sterilization_method: 

### data_sterile_ref.csv

Variable descriptions are the same as data_live_ref.csv


crawford_yan_extractions.csv