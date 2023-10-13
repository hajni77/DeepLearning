# Multiple-Object Tracking

Tracking-by-detection approaches are able to handle a variable number of targets over time. This property is crucial for online tracking in autonomous driving applications. Drawbacks, however, arise from detection errors, which are for example missing objects or False Negatives (FNs) and false detections or False Positives (FPs), because of clutter. This in turn means, that the performance of tracking-by-detection applications significantly depends on the detection quality. 
Typically, tracking-by-detection consists of four main steps. First, the object detector tries to identify all targets at the current time step. Second, based on the previous states, the model predicts a new state for each object. Afterwards, all predicted states get associated to available measurements. Finally, the model corrects each target state with its assigned detection.

https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w21/Wan_An_Online_and_CVPR_2018_paper.pdf 

"Classical methodologies such as Multiple Hypothesis Tracking
(MHT) and the Joint Probabilistic Data Association
Filter (JPDAF) focused on establishing sophisticated models to capture the combinatorial complexity on a frameby-frame basis."

MOT problem into four steps: 
feature learning, tracklets initialization, data association and trajectory updating

 D. Reid. An algorithm for tracking multiple targets. IEEE
transactions on Automatic Control, 24(6):843–854, 1979.

T. Fortmann, Y. Bar-Shalom, and M. Scheffe. Sonar tracking
of multiple targets using joint probabilistic data association.
IEEE journal of Oceanic Engineering, 8(3):173–184, 1983.
______
2023.09
MAIN Resources
https://github.com/ultralytics/ultralytics

https://towardsdatascience.com/what-i-was-missing-while-using-the-kalman-filter-for-object-tracking-8e4c29f6b795#:~:text=The%20algorithm%20steps,state%20with%20an%20incoming%20measurement.

