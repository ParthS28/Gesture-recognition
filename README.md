# Gesture-recognition

This repository contains a model for real time hand gesture recogniser to detect number of fingers raised using OpenCV.

# Note

This model still has a few bugs. Few bugs that I have noticed - 
1) Every time I try to run the program I need to run it twice. The output it shows the first time is, "Can't receive frame (stream end?). Exiting ...", but if I run it again after this, it works fine.

2) During runtime, if for some reason I do not have a hand or any other object in the 'Region of interest' i.e it can not find any contour, the program crashes. 
