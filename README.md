# Quadcopter Automatic Landing Detection

The aim of this project - create an algorithm/approach which will detect the time moment of a drone touching a surface during the landing. The final algorithm should use only the actual/current data from sensors and motors in the given moment without using data from the external sensors, such as LIDAR, the ultrasonic, or the vision sensor due to the previously mentioned problems. Also, the final algorithm should be used real-time, with limited computation resources.
The final model fits with the project expectations and the benchmark of the project, and finally provides a 0.94 F1 score on the unseen data. The critical moment for this project might have been to find a trade-off between False Positives and True Positives. The first could cause the drone to crash, and the second would cause its drifting, both being negative occurrences.
GMM is a fast clustering algorithm, and scaling training dataset will not significantly impact the training time.


## Project environment
This project use Python 2.7 and Jupyter Notebook for all computatiuons and algorithms' explanation. The best practice is to use Anaconda toolset with all pre-installed python modules and machine learning libraries, also this project use Pandas library.

## Testing and training dataset
The dataset consists of 88084 records with 21 feature. The dataset divided into training and testing parts: raw_data.csv for training purposes and test_data.csv - for testing purposes.
