# sequential-regression-label-interpolation
Given some sequential regression labels for a machine learning task (e.g x,y of object tracking data) how you fill in missing labels if it's only labeled every other frame of video.

## Use case
For my rugby tracking robot, i have video data of a match, and i need to label where the action is happening. Instead of labeling evrey frame of video; i can create one label every 30 frames (1 label per second in 30fps video) and use this code to generate the labels for the inbetween frames so that it can be fed into a machine learning algorithm. 
