# Msc Thesis Crop Type Mapping
 Msc Thesis on Deep Learning architectures for crop type mapping

By Teun de Visser 
e-mail: teun.devisser@wur.nl

Wageningen University


Contains:

pre-processing notebook
    To load sattelite images and shape files. It summarizes the multispectral reflectances per parcel defined in the shapefile and saves the pandas dataframe as a .csv file.
Training notebook 
    Loads saved .csv files back into pandas dataframe and performs a train test split. Model selection is required to train a model of choice. The notebook saves entire models and their respective outputs. Output can be read from this notebook.
model output notebook
    Loads saved model outut .csv files and summarizes them in a new .csv file. How the summary is defined is up to the user. There are code blocks to create summaries of recall values or to create a combined .csv file with all performance metrics of each model in a defined file.
