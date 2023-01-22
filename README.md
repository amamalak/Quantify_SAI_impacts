# Project Description
* __project-name__: Quantify_SAI_impacts
* __author__: Antonios Mamalakis, Elizabeth A. Barnes, and James Hurrell
* __date__: January 2023
* __goal__: We use deep learning and explainable AI techniques to quantify impacts of Stratospheric Aerosol Injection

## Abstract
Stratospheric aerosol injection (SAI) has been proposed to stabilize global warming and limit the associated economic and societal consequences. A comprehensive assessment of the impacts of such an intervention is necessary to inform decision making regarding deployment. Here, we introduce a framework based on explainable artificial intelligence to quantify the impacts of SAI and of any geoengineering strategy. Our framework is advantageous in that it is purely data-driven, non-local, nonlinear, and also accounts for any epistemic or aleatoric uncertainties that might be present in the data. We find that SAI will likely have very diverse impacts on climate, e.g., decelerating changes for many variables like temperature, precipitation and extremes, while having negligible to no impact on e.g., ocean acidification. Our findings highlight the importance of understanding the potential impacts of geoengineering beyond mean-temperature or ensemble-mean responses and suggest the need for further research to fully assess the risks and benefits of such interventions. 

## Run the Code
The notebook "analysis_temp_modelsuite_deepshap" is the main script that reads temperature data and trains a neural network to learn to distinguish between pre- and post 2040 periiods, as described in Mamalakis et al. (2023). It also explains (using the method DeepSHAP) the predictions of the network and saves all relevant results in a directory. Similar notebooks need to be written and run to analysze any other variable of interest beyond temperature. The results for all variables analyzed in Mamalakis et al. are provided in the directory "results_all_deepSHAP". Lastly, the notebook "analysis_summary" produces summarizing plots as in Mamalakis et al. 


## Data Access
* Data can be accessed at this url: https://www.earthsystemgrid.org/dataset/ucar.cgd.ccsm4.ARISE-SAI-1.5.html and https://www.earthsystemgrid.org/dataset/ucar.cgd.cesm2.waccm6.ssp245.html
* Post-processed (concatenated and/or interpolated) data should be stored in a directory that is within the project directory together with the main scripts.

## Relevant publication
in preparation...

# Extra Information

## License
This project is licensed under an MIT license.

MIT © [Antonios Mamalakis](https://amamalak.wixsite.com/antonios)
![image](https://user-images.githubusercontent.com/72468665/213895466-4eddf904-62e1-4fb7-a3b0-2504d7b2f1f3.png)
