# COMPSCIX433.3
Final Project

Goal: Analyze historical CAISO data and identify methods for determining "high demand days" and using FFT to determine cycles of energy trends.

Python version: 3.9.7

Getting started:
The csv file is too large to upload here. Go to the following link below to have it automatically downloaded. Rename the file or the read_csv line within the notebook. If rerunning the API to obtain caiso data, you can read_csv to your new file. Subsequently, run all cells in order.

File download:
[caiso_data.csv](https://buildingviz-api.s3.amazonaws.com/output/caiso/all_20180410_20230801_401074.csv?AWSAccessKeyId=ASIAZHYIUUBGEZ3E5RIS&Signature=o5trgQNCvK%2FsFseCHVnXb5tQzYM%3D&x-amz-security-token=IQoJb3JpZ2luX2VjEKn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMSJIMEYCIQDGLywJDUbWq8FtVsinhphhGwodViOcVPaIT3EhcykTmAIhANLA7he39CVYh7GuA%2B6g5mVgEjnNM92UHIoX3g1LSeZoKvQCCGIQAhoMNjM1MTM2NDE3ODY4IgwwDoZehmrIUE%2BVhBMq0QJEatPVNgR7XE0kqeY6ag4rH4AGhU2ni9MZLGuVCpdJKTOARK8nIh3miBYCnR91t%2BOAdQ7uXUM5egwNHb2RXAcz0yV%2FkMytCXTEaLt49nzOLXotu8zddda4%2BuXah%2FQZ02DzcSNfLPDSpCo8FbIwyID5YSz1Igkd0vvlta7ENIFnaAWE2HNYD8P%2Fv3HAhgBI2s4L5ppuBjTky9dyO6JrQ0nyhXqHCMuyAFq%2Bs9Bnh2YYs2oE2Y6ydggli9cCW9JTFeoXakYM9b07rOnEf8f86ARlxI3BQlncqTA6Im0TJTBjvNhQeEBi7nftyY7iRNErbCYd%2Fh%2BBtM%2FIXL3E3a5CsgKKTLu0VitUWFwqzO3gX124B9q7q1ib1oOVHLueMwi9qlr29U%2F9wI1UMxoEU9jtpO%2B0z2gZtbvF93tGITExi%2Fh1DYPqCQ1ICHm2pm65LECmcbzXMLiG9KYGOp0BSo7IbeAG7TzdVAaYO3%2FLmmcjg2A5bnvR3ep6qsVelhVC29ZRSzT36shFYVZJHZztMNzfOTt6BOYDiEux0l4QR%2BRxRXcfYRC4X5Fha4%2BojzCHVyETM4aN6GmnHKqQ%2BDHvimaTEL%2FLWo2P7t7ReDTlWV6TQjfDh7DicvK6bSW%2BBrbe6HnLutrcmDtXesHs7mAh93t1zPOgMyRLiEnsNw%3D%3D&Expires=1692209824)

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
