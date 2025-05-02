# Directions for Applied Remote Sensing Final

For Dr. Anna Schweiger's Applied Remote Sensing Final Report:

1. Analysis of Polarizations and spatial resolution:
   - data acquisition:
     - code for data acquisition is found in initial
     - each combination of polarization and spatial resolution have the naming convention  'sar_processing_pp_rm.ipynb'. Because VV polarization was identified as being better at penetrating through the canopy, the files with 'vv' in the name are better developed.
   - data analysis:
     - code for data analysis of the spatial resolution to move forward with is in the python notebook 'differencing.ipynb'. The block of code for the Moran's I test is at the bottom of the notebook.

2. Analysis of cumulative growth rates in treated and untreated forest
   - Data acquisition is can be found in SAR_initial folder in the file 'sar_processing_vv_10m.ipynb'
     - the separation of pixels based on presence within or outside of treatment areas occurred in ArcPro
  - Data analysis:
    - 'forestTreatments' -> 'ratioplot.ipynb'
    - the code for the plot can be found in the block of code with '## CUMULATIVE CURVE PLOT ##' commented out at the top and the block of code beneath it that was made for this course to be easier to read. 
