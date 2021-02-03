# CaseStudy2Final
Code submission for Case Study 2 project work

Goal: Estimate absolute pose of cars (6 DoF) in a real words environment using images taken from vehicle mounted camera. 

Presentation: https://github.com/rbewoor/Pose_Estimation_Autonomous_Driving/blob/master/FinalPresentation_PoseEstimationAutonomousDriving.pdf 
Report: https://github.com/rbewoor/Pose_Estimation_Autonomous_Driving/blob/master/FinalReport_PoseEstimationAutonomousDriving.pdf 

Data provided by Kaggle: 4,200 images containing 10 cars on average per images. Ground truth values for pose provided for all these images.

Trained two nerual networks for evaluation: Centernet with ResNet-18 backbone, and Centernet with ResNeXt-50_32 backbone.

Use case created for the trained models: Decide whether to allow the autonmous car controller to hand over manual control to a driver. Using the pose estimates from Centernet model, we would recommend a suitable driver level (Beginner, Medium, Advance, Not Allowed) skill-level required to allow manual switch from autonomous model. Based on the profile of the driver, the recommended level is compared with the actual level of potention driver and then control handover would be decided.


