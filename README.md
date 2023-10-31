# GeoAI-Challenge-for-Air-Pollution-Susceptibility-Mapping
Submissions for username JuliusFx for the above ITU problem statement

This repository contains the following files

  1. Technical Report - gives the summary of the model developed
     
  3. main.ipynb- the jupyter notebook used to generate the predictions
     
  4. The datasets provided
     
       a) Train.csv-contain train features
     
       b) Test.csv-we are supposed to predict the aqi values for the 160 location in the city of milan
     
       c) air_pollution_Milan_Comune_topo_only.csv-contains topological features for the city of milan
     
       d) Interpolated seasonal datasets from the city of milan from a regular grid
     
           i) meteo_autumn_2022
     
           ii) meteo_spring_2022
     
           iii) meteo_summer_2022
     
           iv) meteo_winter_2022
     
  5. requirements.txt- has the module version required to run the notebook successfuly
     
  7. lgb_sub.csv - contains the predictions for our proposed model

Order of Running the Files
  1. Ensure all files are residing in the same folder. I run them on conda environment in my computer
     
  3. Install the models in requirements.txt
     
  5. Run main.ipynb-should be able to generate the lgb_sub.csv file

To view the competition page where you can get more information on the problem statement, please visit: https://zindi.africa/competitions/geoai-challenge-for-air-pollution-susceptibility-mapping
