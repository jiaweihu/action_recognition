# Action Recognition
Action recognition is one of the subjects in computer vision and machine learning. The related keywords can include action classification, video classification, activity recognition, pose analysis, plan recognition, goal recognition, intent recognition, behavior recognition, location estimation and etc.

Action recognition has been progrerssing very quickly, covering the field of gaming, healthcare, augmented reality, sport and etc. In this lierature review, the recognition of sport activities, such as yoga, taiji, are mainly considered, with the aim of focusing the following aspects:
- Key points and their connections
- Action identification 
- Understand geometric and motion information of the human body

## Contents
 - [Review articles](#Review-articles)
 - [Academic organisations](#Academic-organisations)
 - [Pose Estimation](#pose-estimation)
 - [Competitions](#competitions)
 - [The relavant pages](#The-relavant-pages)

## Review articles
* [A Review of Human Activity Recognition Methods](https://www.frontiersin.org/articles/10.3389/frobt.2015.00028/full) - a bit old review, articles before 2015
* [Which one is the best algorithm for video action recognition?](https://medium.com/apache-mxnet/which-one-is-the-best-algorithm-for-video-action-recognition-298fb5c4ad4f) - GluonCV 0.9.0 provides a large model zoo for video action recognition and tutorial
* [A Comprehensive Study of Deep Video Action Recognition](https://arxiv.org/abs/2012.06567) - Amazon, summary of video action recognition research papers till 2020
* [Literature Survey: Human Action Recognition](https://towardsdatascience.com/literature-survey-human-action-recognition-cc7c3818a99a) - Brief human action recognition literature survey of work published between 2014 and 2019.
* [Awesome Action Recognition](https://github.com/jinwchoi/awesome-action-recognition#pose-estimation)
* [Paper and Code on Action Recognition](https://paperswithcode.com/task/action-recognition-in-videos) - includes benchmarks, libraries, datasets, etc.
* [A gentle introduction to human activity recognition](https://indatalabs.com/blog/human-activity-recognition?utm_source=facebook-gr&utm_medium=sharing&fbclid=IwAR0Iqkq4gVztJxpFnpUZWsc6lnnwRhmV4gv1gHtj_ZBQL6OX6-33fW4fpAE) - from Indatalabs, involves data acquisition, pre-processing, feature extraction, classification.


## Academic organisations
* [Human Action Recognition, The Alan Turing Institute](https://www.turing.ac.uk/research/research-projects/human-action-recognition) - the ‘path signature’ technique is being used to represent streamed body pose data.
* _[Action Recognition in Video, University of waterloo](https://uwaterloo.ca/vision-image-processing-lab/research-demos/action-recognition-video) - on local salient motion feature detection, action representation, and action classification_


## Pose Estimation
### Human Pose Estimation Literature
* [VISO.AI, Human Pose Estimation with Deep Learning – Ultimate Overview in 2022](https://viso.ai/deep-learning/pose-estimation-ultimate-overview/) - by Elisha Odemakinde, promoting VISO Suite
* [A Comprehensive Guide on Human Pose Estimation](https://www.analyticsvidhya.com/blog/2022/01/a-comprehensive-guide-on-human-pose-estimation/) - by Mrinal Singh Walia
* [V7labs: A Comprehensive Guide to Human Pose Estimation](https://www.v7labs.com/blog/human-pose-estimation-guide) - by Nilesh Barla, PerceptronAI
* [Human pose estimation with deep learning: Overview for 2022](https://blog.superannotate.com/human-pose-estimation-with-deep-learning/?msclkid=8a7ae7edc24311ecb8e6e3c985afb67e) - blog of superannotate

### Pose Estimation Platform
* [AlphaPose](https://github.com/MVIG-SJTU/AlphaPose) - PyTorch based realtime and accurate pose estimation and tracking tool from SJTU.
* [Google mediapipe](https://google.github.io/mediapipe/) - MediaPipe offers cross-platform, customizable ML solutions for live and streaming media..
* [OpenPose Library, CMU](https://github.com/CMU-Perceptual-Computing-Lab/openpose) - Caffe based realtime pose estimation library from CMU.
* [GluonCV](https://medium.com/apache-mxnet/which-one-is-the-best-algorithm-for-video-action-recognition-298fb5c4ad4f), a Deep Learning Toolkit for Computer Vision 
* [Detectron2, Facebook AI Research](https://github.com/facebookresearch/detectron2/), detection and segmentation algorithms 
* [MoveNet: Ultra fast and accurate pose detection model, Tensorflow](https://www.tensorflow.org/hub/tutorials/movenet), models that detect 17 keypoints of a body and run faster than real time (30+ FPS) 

### Commercial systems
* [Action recognition, Google](https://cloud.google.com/video-intelligence/automl/docs/action-recognition) - cloud service for video classification and object tracking.
* [AI Pose Estimation Engine, next-system](https://www.next-system.com/en/visionpose) - Visionpose, real-time 2D/3D human skeleton detection with 30 keypoints.


### Pose analysis cases
* [LearnOpenCV: Body Posture Analysis](https://learnopencv.com/building-a-body-posture-analysis-system-using-mediapipe/?ck_subscriber_id=1142852616) - An introduction sample using side view to build posture alert using MediaPipe.
* [Nicholas Renotte: Sign Language Detection](https://www.youtube.com/watch?v=doDUihpj6ro&t=5272s) - Sign Language Detection using ACTION RECOGNITION with Python | LSTM Deep Learning Model, code: https://github.com/nicknochnack/ActionDetectionforSignLanguage

## Competitions
* [ActEV: Activities in Extended Video](https://actev.nist.gov/sdl) - Activity detection in security camera videos. Runs through 2021. Hosted by NIST.


## The relavant pages
### Articles
[Human Action Recognition using Detectron2 and LSTM](https://learnopencv.com/human-action-recognition-using-detectron2-and-lstm/)
- Code: https://github.com/spmallick/learnopencv/tree/master/Human-Action-Recognition-Using-Detectron2-And-Lstm

### Datasets
[RNN for Human Activity Recognition - 2D Pose Input](https://github.com/stuarteiffert/RNN-for-Human-Activity-Recognition-using-2D-Pose-Input#dataset-overview)

### Areas of interest
[Teaching Computers to Recognize Human Actions in Videos](https://towardsdatascience.com/teaching-computers-to-recognize-human-actions-in-videos-81b2e2d62768) - -Predict & cluster: Unsupervised skeleton based action recognition
- PREDICT & CLUSTER: Unsupervised Skeleton Based Action Recognition, Kun Su, Xiulong Liu, Eli Shlizerman, https://arxiv.org/abs/1911.12409
- https://towardsdatascience.com/tagged/action-recognition

### Relevant applications
- AI powered personal trainers. Keeping physical well-being is an important part of our life these days. A good trainer can be very helpful for us to reach desired fitness level. The market is becoming saturated with apps that harness the power of AI to guide training. For instance, Zenia (https://apps.apple.com/us/app/yoga-for-beginners-zenia-app/id1483602673) is an AI-powered yoga app that guides you towards achieving a proper posture. It uses the camera to detect your pose and estimates how accurate your pose is—if it is correct, then the predicted pose will be represented in green, just like in the image above. If the pose isn't correct, the red color will replace the green one.
Apart from yoga, applications can also be found in other forms of exercise. For example, it is now commonly used in weight lifting, where it can guide app users to perform a proper weight-lift by searching for common mistakes and providing insights on how to fix them to prevent injuries.
- Motion capture and augmented reality. Another interesting application of HPE can be CGI. The entertainment sector, specifically, the cinema business, spends tons of cash to create computer-generated graphics for special effects, mysterious creatures, out-of-the-world sceneries, and a lot more. CGI is expensive because it requires a lot of effort—like wearing special suits and masks to capture the motions, creating superficial effects in the estimated pose, processing power, and also large time investments on top of that. HPE can automatically extract key points from 2d input and create 3d rendering of the same, which can then be used to add effects, animations, and whatnot.
- Athlete pose detection. These days, almost all sports rely heavily on data analysis. Pose detection can help players to improve their technique and achieve better results. Apart from that, pose detection can be used to analyze and learn about the strength and weaknesses of the opponent, which is invaluable for professional athletes and their trainers.
- Motion tracking for gaming. Another interesting application of pose estimation comes down to in-game applications, where players can make use of the motion capturing capabilities of HPE to inject poses into the gaming environment. The goal is to create an interactive gaming experience. For example, Microsoft’s Kinect uses 3D pose estimation (using IR sensor data) to track the motion of the players and to use it to render the actions of the characters virtually into the gaming environment.
