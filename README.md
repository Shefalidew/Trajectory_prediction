This is a part of SMART2 project, which is an advanced integrated obstacle and track intrusion detection system for smart automation of rail transport.
In this project, we predict the trajectory of the detected object by utilizing an LSTM model, using a series of images by UAV as input.

The Stanford Drone Dataset (a large-scale dataset for outdoor drone video footage) is used for the purpose of training. The dataset was created by Stanford University's Autonomous Systems Lab.It consists of 8 video sequences, each between 3-6 minutes lenght. And a total of 10 object classes.Due to overwhelming size of the dataset, a compressed Stanford Drone Dataset was used by Kaggle.

Comparison of Predicted vs Test values
(Four subplots for four features- x_min, y_min, x_max, y_max
![image](https://github.com/Shefalidew/Trajectory_prediction/assets/97191521/3310d87f-4acd-4458-b662-f75ab95adad3)

For visualization of the Bounding box for ground truth and predicted value
Blue box - shows predicted value
Green box - shows ground truth value
Red box - the Initial position 
Red dots - the trail of trajectory

Visualization of Stationary Object, Moving Camera situation
![image](https://github.com/Shefalidew/Trajectory_prediction/assets/97191521/cb0a81b3-5f34-4a72-baab-df2022b7a95b)

Visualization of Moving Object, Moving Camera situation
![image](https://github.com/Shefalidew/Trajectory_prediction/assets/97191521/274a7ee4-b9d7-4afd-b836-1f4b00d000c6)

Visualization of Moving Object (random direction), Stationary Camera
![image](https://github.com/Shefalidew/Trajectory_prediction/assets/97191521/0752ac14-cdbc-48fc-ac57-b4eea948d2f8)
