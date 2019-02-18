# plasma-analysis-notebooks
In this repository you will find a number of Jupyter Notebooks that can analyse the .csv files we have from the Oscilloscope and Spectrum Analyzer. The signals originated either from a signal generator to test the amplifier or from the plasma chamber to record experimental data.

## Reading_Cleaning_Displaying_Data-2018-10-04.ipynb
In this Notebook you can see the process I have gone through to take the .csv files created by the Rigol DSA710 Spectrum Analyzer and extract only the necessary data to create plots of the spectrum, including identifying any peaks.

## Signal_Analysis_Oscilloscope-2018-10-04.ipynb
This Notebook extracts data from the .csv file created by the Tektronix 2024B DSO (Digital Storage Oscilloscope) to create a plot, measure the peak-to-peak voltage and frequency and calculate the gain. 

## Plots and Analysis of Spectral Data.ipynb
The plotting of experimental spectral data and its analysis is covered in this Jupyter notebook. 
The instantaneous and average power spectra are plotted comparing the different signals received from 'antennas' of different lengths inside the plasma chamber. 
Initial analysis of this data was also carried out in this notebook to determine electon plasma and gyro frequencies.
