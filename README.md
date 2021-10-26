# BioMedical-Image-Analysis-System-SimpleITK

This work was presented for a BioMedical Imaging Class at SFSU in Spring 2021.
### The assignment:
We will target building and experimenting a system that analyzes chest CT scans of Covid-19 patients. Each group will consist of about 5-6 students including graduate students who may act as team leads who mentor other undergraduate members. With data provided, each group will identify, design, implement and evaluate specific data analysis algorithms. For coding platform, students will use Insight Segmentation and Registration Toolkit (ITK: http://www.itk.org/) with C++ or (SimpleITK: https://simpleitk.org/TUTORIAL) with Python.

The CT Scans of the COVID-19 patients were borrowed from https://www.cancerimagingarchive.net,
NBIA Data Retriever was used retrieve the DCM files (.DICOM) in order to later be read by Fiji
or ImageJ. Using Jupyter Notebook and SimpleITK with Python I was able to experiment image 
registration through use of optimizer, interpolator, and similarity metric methods. 
Using the following choices with respect to initialization and registration component settings:
Similarity metric, mutual information (Mattes MI), Interpolator sitkLinear(), Optimizer Gradient 
Descent– I was able to improve the spatial correspondence between sepcific coordinate points on the
CT Scan of the COVID-19 patient. 

### How To View Notebook:
Download code as a ZIP File and open the .html file to see the non-interactive Jupyter Notebook.
To view the actual code in Jupyter Notebook, make sure Jupyter Notebook is installed and open the
.ipynb file. The notebook will not properly display the GUI since the image configuration/location
is not the same.
