# FORECASTING SOLAR IRRADIANCE FOR SOLAR FARMS IN RAJASTHAN
Forecasting Solar Irradiance using LSTM and optimizing parameters using Bio-inspired algorithms

This project has employed LSTM for forecasting hourly solar irradiance on the dataset obtained from NREL website. Bio-Inspired algorithms have been used on this endeavour to optimize the results of forecasting and to find the best fitted technique. Python was used for the analysis using keras for deep learning.

Description of Dataset:
Dew Point - Temperature to which air must be cooled to become saturated with water vapor. SI unit is degree Fahrenheit
Temperature - The intensity or degree of heat present in atmosphere. SI unit is Kelvin (K)
Pressure - The pressure exerted by the weight of the atmosphere. SI unit is pascal (Pa)
Relative Humidity - The amount of water vapor present in air
Wind Speed - The rate at which air is moving in a particular area. SI unit is meters per second (m/sec)
Global Horizontal Irradiance - Global Horizontal Irradiance (GHI) is the total amount of solar irradiance received horizontally to the ground. This is the quantity used for measuring how much sunlight falls directly on the solar PV cells which is later used to make electricity. Its SI unit is W/𝑚2.

Each of the 43800 are described by the time at which they recorded like Year, Month, Day, Hour and Minute while it depends on six features.

For the forecasting of solar irradiance using the other features, LSTM which is a deep learning was employed which uses back propagation with feed forward neural networks.

Bio-inspired algorithm focuses on the designs and developments of computer algorithms and models based on biological mechanisms and living phenomena. The basic principle is that all individuals, i.e. the systems that collaborate on an overall task, follow simple rules that lead to an emerging behaviour.

# Cuckoo Search optimization
In the cuckoo search optimization algorithm, the cuckoo population is initialized first. The eggs are laid into a variety of nests and only the best ones survive to grow up and the nest they grow up in are the best solutions. The location of these nests are found out to be the best locations towards which the next set of eggs are laid to produce the best solution. This cycle of finding the best nests to lay eggs continues over the number of iterations, where the worst eggs are eliminated and the best solutions are taken forward.
The initial location of the nests is determined by Levi flight method which is a random walk derived from the foraging patterns of birds and insects. The creatures travel in a straight flight path followed by a sudden 90° turn leading to a levy flight pattern. 


# Grey Wolf Optimization
The Grey Wolf Optimizer uses a wolf population and calculates fitness for search agents and over iterations, it updates the wolf positions to hunt the prey. The discussion about optimization problems always includes an objective function which needs to be optimized. In our project the objective function is the accuracy of LSTM integrated with GWO.
