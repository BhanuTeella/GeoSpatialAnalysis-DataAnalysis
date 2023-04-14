# TravelDataAnalysis
The programs are used to perform analysis on trips travelled by users for various activities. This repo has two files one calculates Distances on each trajectory by each user. The  other program is used to create maps on the data. The program uses multiprocessing to handle large datasets.

The dataset is assumed to have columns latitude, longitude, altitude,time-stamp trajectory_id and individual_id where each row corresponds to a location point in a particular trajectory for an individual. Trajectories correspond to outdoor movements, including daily routines such as commuting and non-routine activities like leisure and sports.
