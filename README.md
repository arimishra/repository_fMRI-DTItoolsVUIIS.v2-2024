Functional and DTI Data Processing Manual












Arabinda Mishra, PhD
Sr Imaging Scientist, VUIIS
Department of Radiology
Vanderbilt University Medical Center (VUMC)










## THE NEW RELEASE UPLOADED ON DECEMBER 2025 (CLICK the latest version for ZIPPED FILES to the right)

## The earlier version on parent folder with few codes needed for secondary application were uploaded for 2023/24 publications
## as required by journals






1.	Introduction:

This manual helps run resting state functional connectivity and stimulus driven activation analysis, structural (DWI: Diffusion Weighted imaging) 
parameters as basic features, and performs parcellation of functionally heterogenous regions using ANN based clustering technique. It implements 
self-organizing map (SOM), a specific unsupervised neural network to segregate functionally heterogeneous regions taking connectivity measures 
associated with each voxel with rest of the brain. Dynamic functional connectivity and diffusion parameter estimation using DWI data are recently 
added to the analysis. The user also has the choice of saving the preprocessed data for both resting state and stimulus data for custom analysis. 
The development of an open-source graphical user interface (GUI) will make these tools accessible to researchers from diverse backgrounds in MRI 
research and ultimately may be adapted for human neuroimaging studies.

The image processing toolset and associated code are saved in 4 folders. Some test fMRI and DTI data are also saved in the folders codePreprocess_fMRI 
and codePreprocess_DTI respectively. Code to process macaque brain acquired on Phillips 3T are in folder codePreprocess_fMRIbrain. These codes are used 
to preprocess or get the data ready for analysis by the toolbox. The registration of fMRI/DTI data into template space is performed before group analysis 
using resting, stimulus state, dynamic connectivity and data driven parcellation is performed. The folder FCAnalysis(VUIIS) is required to be on the matlab 
path and stored in the exp: spm12/toolbox/FCAnalysis(VUIIS) folder.
