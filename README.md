# NASA Space Apps Challenge 2018 - Tartu
You can find the the main functionality located in console.py. This file takes argument --city, which specifies folder where to look for input data. Input data should be images with brightness temperature, Normalized Difference Vegetation Index (NDVI), soil sealing percentage, NASA night lights product, Terrain Ruggeddness Index, SRTM digital elevation model, VK.com (no longer valid) geotagged photographs, road network data, population and population density data for specific region.<br>
As output will be provided estimated number of population in given region. By default, it uploads model weights from trained_models/model.hdf5 file.
To train new model, run train_model.py. By default it uses samples from data/Tallinn folder, and creates 10 augemented images for each map. Model will be saved to train_models folder. Folder augemented_examples contains examples of original and augemented images. Original image will always be with index 0.<br>
In data/population_statistic folder there is a file with number of people in each Estonian city for last years. Population number column was used as target variable. 
Folder data/Tallinn contains example of input data. 

## Team Starships
slavikkom - [Viacheslav Komisarenko](https://bigdata.cs.ut.ee/viacheslav-komisarenko-2019) <br>
ask4jubad - [Jubril Gbolahan ADIGUN](https://linktr.ee/ask4jubad) <br>
karasov - [Oleksandr Karasov](https://researchportal.helsinki.fi/en/persons/oleksandr-karasov) <br>
burdun - [Iuliia Burdun](https://research.aalto.fi/en/persons/iuliia-burdun)<br>
myskovik - [Viktor Mysko](https://www.linkedin.com/in/viktor-mysko-1b8528b8/?originalSubdomain=ua)
