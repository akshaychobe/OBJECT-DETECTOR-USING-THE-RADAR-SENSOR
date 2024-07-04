# Object Detector Using The Radar Sensor
======================================================================================================


**Introduction**
Object detection is a crucial task in many autonomous systems, such as self-driving cars, drones, and robotics. This project aims to develop a robust algorithm that can detect and track a moving object in a radar point cloud dataset.

**Dataset and Pre-processing**
The dataset used in this project is a radar point cloud dataset collected by a pulsed radar sensor. The dataset consists of 294 frames and 295 frames, each frame containing a 3D point cloud of the scene.

**Intersection Algorithm**
The algorithm consists of four steps: isolating dynamic objects, filtering and calculating the centre of cluster, evaluating the result, and implementing the intersection algorithm.

### Isolate Dynamic Objects
Separate dynamic and static points from the radar point cloud using a velocity threshold of 0 m/s.

### Filtering and Calculating the Centre of Cluster
Filter out irrelevant data points from the surrounding environment and calculate the accurate centre of the object.

### Evaluate the Result
Compare the calculated centre points with the ground-truth from the dataset and evaluate the accuracy of the algorithm.

### Implementation of Intersection Algorithm
Apply the algorithm to the unlabeled dataset and calculate the distance of the object using the intersection algorithm for radar sensor.

**Conclusion**
The project presents a simple object detector using radar sensor data. The algorithm is robust and can detect and track a moving object in a radar point cloud dataset with an accuracy of more than 90% at a threshold value of 2.1m. The algorithm can be further optimized and tested in real-world scenarios before it can be used in an actual vehicle.



Note: This README file is a summary of the project report and is intended to provide a brief overview of the project. For more details, please refer to the project report.
