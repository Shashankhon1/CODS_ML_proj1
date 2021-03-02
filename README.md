# CODS_ML_proj1

# temp Readme.md

OBJECTIVES:
To try and make existing lane detection systems using Hough line transformation more robust and reliable and improve the existing barrier detection using MRF model and use this to predict a safer navigation of the autonomous body using DNNs.

RELEVANCE:
With the growing trend to automate vehicles, a strong foundation is required in the entire navigation domain. Making a navigation system that is safer, would provide a huge edge, especially to the smaller industries related to the domain mushrooming in India.

Most of the object detection system are unidirectional and work only for superficial obstacles and not the obstacles hidden in the background, which can still prove to be hazardous. 
By fusing gradient potential, curvature prior potential, and depth variance potential, we can easily classify most of the obstacles in a given environment , there by making the obstacle detection unit exponentially safer.
The Lane detection, at the moment, works best only if the given lane separator is the most dominant line in a given environment. Though the system can be efficient in large well spaced lanes, it might not be the most efficient mechanism in the everyday, real world scenario.
The idea is to merge basic RNNs and CNNs with Hough line transformation, so that the program can recognise an actual lane, despite it encountering several dominant straight lines in the exposed environment, there by making the lane detection system far more robust.

Datasets : 
https://bdd-data.berkeley.edu/
