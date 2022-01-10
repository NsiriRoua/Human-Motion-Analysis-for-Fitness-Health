# Yoga Pose Detection 
![image](https://user-images.githubusercontent.com/69841466/148768042-8417b879-93e9-4a3c-a9c7-88e555b102dd.png)

## project Description 

Pose estimation is a hot topic now-a-days. It is being used in video-surveillance system to sport analysis tasks. Some of the classical problem can be solved using pose estimation like: person count in a frame, fall detection, smart fitness tracking app etc. Basicly by using pose estimation we can observe the movement of human and take any decision Before of deep learning arena HoG and SIFT based approach used in feature extraction. But because of CNN these feature extraction process become more accurate using lots of data.
So,Using PoseNet we get key points of human limbs. Output of keypoints is (x,y) co-ordinate value. Then using these keypoints we can determine angles of different limb of our body or can use these point in classifier model for human acitivity detection. There are some out performing model for pose estimation like: OpenPose pose estimation model which can also be inferenced in CPU.
Our mission is to detect 4 yoga poses :
      * Donwdog
      * Warrior
      * Plank
      * Tree
      * Doddess

So 
This Project is based on [PoseNet](https://www.ri.cmu.edu/publications/openpose-whole-body-pose-estimation/), and [VGG19](https://keras.io/api/applications/vgg/)

## Workflow 

![image](https://user-images.githubusercontent.com/75584699/148693526-54373f57-79ed-440a-bf82-3e527e799d48.png)

  
 - Dataset_Creation
   * collect yoga pose videos from youtube  
   * divide videos into small frames (subclips)
   * Resize and normalize 
   * Split data into train and test

You can find the dataset [here](https://drive.google.com/drive/u/3/folders/1xlw6pUuwmZ0Rc5unzQRI9_Lc1teZBXcU?hl=fr)

 - Yoga_Poses_Detection
   * Detecting poses in the frames
   Notice : For real time detection , we need to place 0 in the VideoCapture method
   
   
 - Whole_Body_Pose_Estimation
   * Data Augmentation 
   * Build the Model : VGG19
 
## Used technologies and Libraries
- python 4.6
- moviepy 1.0.2
- OpenPose
- OpenCV
- Tensorflow
-  
- Jupyter
- Collab


## Results 

[Videos](https://drive.google.com/drive/u/3/folders/12ibn0Ogqkyh46CNXgm66ZjnUjEeUHEjp?hl=fr)

[Models](https://drive.google.com/drive/u/3/folders/1vZeNEdRlt_ZdI08lGfCZg8FAdkdx4Bwy?hl=fr)

