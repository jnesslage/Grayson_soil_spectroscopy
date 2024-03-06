# Grayson_soil_spectroscopy
A VIS-NIR soil spectroscopy dataset for data analysis

Benchtop Data Collection Steps:

FORTHCOMING!

Spectral Pre-Treatment Steps:

All spectral pretreatment steps were performed using R 4.2.2. using the prospectr package. The details are provided in the RMarkdown document named Grayson_spectral_preprocessing.Rmd. The baseline spectra, which have been smoothed using a Savitzky-Golay (SG) filter with polynomial order of 3 and a window size of 25, can be found under Grayson_savistzky_golay_spectra.csv. The derivative of the SG spectra is named Grayson_savitzky_golay_derivative.csv. Continuum removal was also applied to the SG baseline spectra and the data can be found under Grayson_continuum_removal.csv. Finally, a PCA of the baseline SG spectra was also added. 

Correlation Plots:

To aid in analysis and modeling, I have provided a series of Pearson's correlation plots for each of the 4 datasets and % total C.



![alt text](https://github.com/jnesslage/Grayson_soil_spectroscopy/corr_plot_sg.png?raw=true)
