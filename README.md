# Human_Pose_Comparison

Technology used is Mediapipe with opencv,python

Steps Followed:

1. Process the video with CV commands and apply media pipe.
2. Extract the Test points(x,y) of points excluding facial. 
3. Normalizing the data for better results.
4. Extracting the Points for Model and normalizing them.
5. Applying Dynamic time warping for comparing the two human poses.
6. Plotting the percentage of score at each instant of time i.e epoch of a video process.

Upload the pynb file and the two videos to be tested.
(This code is for comparing to single poses i.e avoid having multiple persons in the video)
(Installing pip files is part of the code)
