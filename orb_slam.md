### ORB SLAM ###

ORB SLAM consists of 3 threads:

1. Tracking
2. Local Mapping
3. Loop Closing (Place Recognition)

## Tracking Thread ##

Tracking thread is in the charge of:
1. Initializtion of the system
2. Pose estimation for every input frame
3. Inserting `Keyframe`s whenever needed.



