# BioMedical-Image-Analysis-System-SimpleITK

The CT Scans of the COVID-19 patients were borrowed from https://www.cancerimagingarchive.net,
NBIA Data Retriever was used retrieve the DCM files (.DICOM) in order to later be read by Fiji
or ImageJ. Using Jupyter Notebook and SimpleITK with Python I was able to experiment image 
registration through use of optimizer, interpolator, and similarity metric methods. 
Using the following choices with respect to initialization and registration component settings:
Similarity metric, mutual information (Mattes MI), Interpolator sitkLinear(), Optimizer Gradient 
Descent– I was able to improve the spatial correspondence between sepcific coordinate points on the
CT Scan of the COVID-19 patient. 

The .ipynb file will not properly display the GUI's seen in the HTML file since the original CT
Scans are not attatched.
