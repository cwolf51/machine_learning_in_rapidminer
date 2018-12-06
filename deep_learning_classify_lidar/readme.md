# Use Deep Learning to Classify LiDAR Points

1. Load the [LiDAR Points](https://github.com/xbwei/machine_learning_in_rapidminer/blob/master/deep_learning_classify_lidar/Office112.csv) into [ArcScene](http://desktop.arcgis.com/en/arcmap/latest/extensions/3d-analyst/3d-analyst-and-arcscene.htm) and label some points as "wall" or "not wall," and save it as a new CSV file, e.g., office_labeled.
    * <img src="relationship_between_points.JPG" width="500">

2. Read the office_labeled CSV file in the [Deep Learning Model](https://github.com/xbwei/machine_learning_in_rapidminer/blob/master/deep_learning_classify_lidar/deep_learning_lidar_classify.xml) to classify the unlabeled points. Calculate the model performance on the training data and the test data.
    * <img src="deep_learning_1.JPG" width="500">
    * <img src="deep_learning_2.JPG" width="500">

3. Import the predicted points into ArcScene and display the result.
    * <img src="predicted_points.JPG" width="500">
    
4. Things you can do to improve your outcome:
    * Manually label more points;
    * Label points with more classes, e.g., chairs, desks, people, floor, etc.;
    * Use more complicated networks in the Deep Learning model;
    * Use LiDAR points with high point densities.
