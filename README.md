# COMPSCIX433.3
Final Project

Goal: Analyze historical CAISO data and identify methods for determining "high demand days" and using FFT to determine cycles of energy trends.

Python version: 3.9.7

Getting started:
If using caiso_data.csv provided, specify the path to the file. If rerunning the API to obtain caiso data, you can read_csv to your file. Subsequently, run all cells in order.

Packages and Modules:
- Numpy
- Scipy
- Pandas
- Matplotlib

Data Access:
Given the complexity of CAISO OASIS for the data that is required, go to https://rapidapi.com/buildingviz-buildingviz-default/api/caiso/details to run the "caiso" endpoint. It provides supply, demand, and CO2 data starting from April of 2018. 

Comments:
- caiso_data.csv is as of August 1, 2023. You can always change the start and end date within the API inputs to collect more up-to-date information

Motivation:
Considering our current environmental status, decarbonization efforts are of great importance, and with my background in the environmental engineering and my professional experience in sustainability, I thought this project would be great with using CAISO data to pursue energy consumption interpolation and analysis. The aim is to address energy trends that persist in the grid, thus contributing to more sustainable energy management. Given that CAISO’s grid is much cleaner than most in the U.S. (aside from NYUP), I thought it would be a great exercise to see what the risks are to the current and future grid.
