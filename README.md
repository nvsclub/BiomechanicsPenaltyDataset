# BiomechanicsPenaltyDataset

## Description
This repository contains datasets built with computer vision techniques, regarding technical movements in sports.

### penaltiesv1-centernet-hourglass-1024x1024
This dataset contains data extracted from 153 penalties. Data extracted with 'CenterNet HourGlass104 Keypoints 1024x1024' from TensorFlow-Hub. 

#### Misc
Json file contains: 
- detection_boxes
- detection_classes
- detection_scores
- detection_keypoint_scores
- detection_keypoints

    limbs={'nose':0,'left_eye':1,'right_eye':2,'left_ear':3,'right_ear':4,'left_shoulder':5,'right_shoulder':6,'left_elbow':7,'right_elbow':8,'left_wrist':9,'right_wrist':10,'left_hip':11,'right_hip':12,'left_knee':13,'right_knee':14,'left_ankle':15,'right_ankle':16}

    limbs_3d = {'left_hand':22, 'left_wrist':20, 'left_elbow':18, 'left_shoulder':16, 'left_back':13,
    'right_hand':23, 'right_wrist':21, 'right_elbow':19, 'right_shoulder':17, 'right_back':14,
    'nose':15, 'neck':12, 'upper_back':9, 'back':6, 'lower_back':3, 'hip':0,
    'left_hip':1, 'left_knee':4, 'left_ankle':7, 'left_foot': 10,
    'right_hip':2, 'right_knee':5, 'right_ankle':8, 'right_foot': 11}
