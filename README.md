# Pose-Classification
Pose Classification using CNN models

Abstract

Human pose estimation is the method of estimating the pose of a human body from an image or a video. In the past 15 years, it has been one of the key problems studied in computer vision because it has provided many beneficial applications including activity recognition, human-computer interaction prediction, and building blocks for MoCap (marker-less motion capture) technology for character animation to clinical analyses. Recently developed pretrained models such as Open AI utilize image annotations, where a model draws a stick figure diagram connecting the 17 important joints on the human body to create a skeleton of the pose and passes in the annotated image into the classification model. In comparison, other models classify the image with no annotations or use the coordinates of the identified joints. 
In our paper, we evaluate the methods of human pose estimation on distinguishing between correct and incorrect plank postures. Identifying incorrect postures from an image is especially useful in sports and evaluations to prevent or predict injuries and determine performance. 
The methods I used include using different layers of convolutional neural networks and pretrained models provided by tensorflow lite, OpenPose, and Deep Pose. I evaluated the performance of these models using different image sizes and using image annotations or not.
Our results indicate that the convolutional neural network with 2 layers performed best on our dataset. This could mean pretrained human pose estimation models are not effective in specific datasets. Further study will be done using different postures and larger datasets. 

Research notebook: https://docs.google.com/document/d/1NJzxSsBl3Fm9n9ugzdQFs86ofhmng8kyeOacUS9wb2Y/edit

Proposal: https://docs.google.com/presentation/d/1XJQxF1i_8BAEPciHSuHloNCXws6-K3dSaGatntAW1DA/edit?usp=sharing

Email 2redrosen@gmail.com for any questions/comments/concerns
