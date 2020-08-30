# Drowsiness Detection for drivers
The objective of this project is to monitor the facial expressions of the driver and beep an alarm in case the person behind the wheel depicts any sign of drowsiness. Thus, preventing the drowsiness related car accidents.

## Purpose
Many statistical reports show that a significant number of accidents are caused due to drowsy driving. As sleepiness can be detected through facial muscle movements like yawning, eye closing, it can be detected easily through facial recognition. If we find any symptom of driver feeling sleepy, we'll beep an alarm which will wake them up instantly and thus reduce the chance of accident. In today's world there is a need of an effective system like this. The project presented here is a prototype which tries to deal with above mentioned problem.

### Procedure
- Collection of dataset.
- Creation of classifier model with the best possible accuracy(CNN+SVM or XGBoost).
- Trying to reduce overfitting
- Deployment of classifier with the help of opencv and haar cascade.

### Accuracy and Report
<p align="center">
  SVM accuracy
  <img src="https://github.com/RC99/Drowsiness-Detector/blob/master/Output_images/Screenshot%20(118).png">
  XGBoost accuracy
  <img src="https://github.com/RC99/Drowsiness-Detector/blob/master/Output_images/Screenshot%20(119).png">
  XGBoost Report
  <img src="https://github.com/RC99/Drowsiness-Detector/blob/master/Output_images/Screenshot%20(120).png">
  SAMPLE<br/>
  <img src="https://github.com/RC99/Drowsiness-Detector/blob/master/Output_images/output/13.jpg" width=270 height=300 />
  <img src="https://github.com/RC99/Drowsiness-Detector/blob/master/Output_images/output/19.jpeg" width=270 height=300 />
  <img src="https://github.com/RC99/Drowsiness-Detector/blob/master/Output_images/output/21.jpg" width=270 height=300 />
  <img src="https://github.com/RC99/Drowsiness-Detector/blob/master/Output_images/output/images%20(69).jpeg" width=270 height=300 />
</p>
<br/>

Happy Coding!!!
