# Yoga Pose Detection 

## project Description 
Pose estimation is a hot topic now-a-days. It is being used in video-surveillance system to sport analysis tasks. Some of the classical problem can be solved using pose estimation like: person count in a frame, fall detection, smart fitness tracking app etc. Basicly by using pose estimation we can observe the movement of human and take any decision Before of deep learning arena HoG and SIFT based approach used in feature extraction. But because of CNN these feature extraction process become more accurate using lots of data.
So,Using PoseNet we get key points of human limbs. Output of keypoints is (x,y) co-ordinate value. Then using these keypoints we can determine angles of different limb of our body or can use these point in classifier model for human acitivity detection. There are some out performing model for pose estimation like: OpenPose pose estimation model which can also be inferenced in CPU.

So 
This Project is based on [PoseNet](https://www.ri.cmu.edu/publications/openpose-whole-body-pose-estimation/), and [VGG19](https://keras.io/api/applications/vgg/)

## Workflow 

![image](https://user-images.githubusercontent.com/75584699/148693526-54373f57-79ed-440a-bf82-3e527e799d48.png)

  
 - Dataset_Creation
   * collect yoga pose videos from youtube  
   * divide videos into small frames (subclips)
   * Resize and normalize 
   * Split data into train and test

 - Yoga_Poses_Detection
   * Detecting poses in the frames
   
   
 - Whole_Body_Pose_Estimation
   * Data Augmentation 
   * Build the Model : VGG19
 
## Used technologies 
- python 4.6
- moviepy 1.0.2
- Jupyter
- Collab


## Results 
https://l.facebook.com/l.php?u=https%3A%2F%2Fdrive.google.com%2Ffile%2Fd%2F1-AKfAcuiSZscH6vxY6FT8OUzDWM2TwOd%2Fview%3Fusp%3Dsharing%26fbclid%3DIwAR3wrQnsdcYOwMIXw5PWxaRwmTeE1H7uWCkviMdCbIm3wxh8m1Lcq9X7pss&h=AT0aZBINCDvV-uPoPOm-k4BgGw1-lUlVDhqDdi-IQZIbCIULJhyRvzHzFtQaQlU-ZUZNcp9UI2zoNvFM8wvDl6vCqgImHvoqlksAb5BK4Ot16QYFmnLYKM0b6AD8yOwJpEeT_w

