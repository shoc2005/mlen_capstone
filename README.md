# Quadcopter Automatic Landing Detection

The aim of this project - create an algorithm/approach which will detect the time moment of a drone touching a surface during the landing. The final algorithm should use only the actual/current data from sensors and motors in the given moment without using data from the external sensors, such as LIDAR, the ultrasonic, or the vision sensor. Also, the final algorithm should be used real-time, with limited computation resources.
The final model fits with the project expectations and the benchmark of the project, and finally provides a 0.94 F1 score on the unseen data. 
The critical moment for this project might have been to find a trade-off between False Positives and True Positives. The first could cause the drone to crash, and the second would cause its drifting, both being negative occurrences.


## Project environment (based on Python 2.7)
Necessary modules:
1) pandas (18.1 or greater)
2) numpy (1.11 or greater)
3) matplotlib (1.5.1 or greater)
4) iPython (4.2 or greater)
5) scikit-learn (0.18.0 or greater)
6) scipy (0.17.1 or greater)
7) jupyter notebook (1.0 or greater)

The best practice is to use [Anaconda](https://www.continuum.io/downloads) toolset with all pre-installed python modules and machine learning libraries.

## About testing and training dataset
A dataset consists of 88084 records with 21 feature. The dataset divided into training and testing part: raw_data.csv for training purposes and test_data.csv - for testing.

## How to run
After the Python envirnonment setup is done. In command line type: jupyter notebook
This will launch a new browser window (or a new tab) showing the Notebook Dashboard, a sort of control panel that allows (among other things) to select which notebook to open.
[More info about this here](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)
