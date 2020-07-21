# Social-Distance-Detector
The project is used to detect weather the distance between people walking

It use YOLOv3 detector which is a pretrained model.
Feed a video input to the model and it will return an output video with people detected. 
If the distance between 2 people is large enough,than they are enclosed in a green box and if the case isn't , than a red box is shown.
Centroid tracking system is used to calculate the distance betwen two people.


