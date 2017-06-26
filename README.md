# morality_lab
Scripts written for the Morality Lab at Boston College

## About:
These are a sampling of data analysis/processing scripts I wrote as lab manager for the Boston College Morality Lab (2015-2017). 


While most of them existed before April 2017, they were kept in the lab GitHub (@lypsychlab) and most changes were not tracked.

## Guide to scripts

* convert_to_BIDS.py: wrangles old fMRI datasets into BIDS format for upload to [OpenfMRI](https://openfmri.org/)
* matlab_tutorial.m: a cute little overview of Matlab programming, designed for research assistants with no coding experience
* test_yl_nipype_MASTER.py: testing suite for the below, based on unittest
* yl_nipype_MASTER.py: constructs a neuroimaging pipeline with [Nipype](https://github.com/nipy/nipype) from a parameter file
  * designed for users who may not be able to write their own Python/Nipype code
* younglab_svm.m: implements leave-one-out binary SVM classification on neural data
* younglab_svm_leavetwo.m: implements leave-two-out SVM classification
* /RSA: behavioral and neural data processing scripts for Wasserman et al. (submitted) 
  * the manuscript based on this code is available [here](http://moralitylab.bc.edu/wp-content/uploads/2017/04/dis_manuscript_d2.pdf)

