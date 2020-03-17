# Trajectory-Transportation-Classifier
In this project, a hierarchical classifier for transportation type, based on trajectory data, has been developed. 

## Features
Trajectory data is a point-based data that needs to be processed to extract the required features for the classifier. The Features that are used are distance, speed, acceleration, and bearing. 

## Hierarchical classification
In this project, hierarchical classification, which a classification method to first distinguish between categories and then classify exact labels, is used. This procedure helps us to focus on the detailed differences in each category. For example, separating a bus from a taxi would be easier when the classier doesn't have to learn the features of the trains.

## Results

The results of the classification task are shown and compared in the jupyter notebook.
