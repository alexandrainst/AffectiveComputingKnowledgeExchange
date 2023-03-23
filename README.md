# Affect Recognition Knowledge Exchange
<!-- write a short introduction -->
This repository is a collection of datasets, models and approaches for affect recognition. The goal is to provide a comprehensive overview of the current state of the art in the field of multimodal affect recognition. The repository is structured as follows:

* [Datasets](#datasets)
* [Models and Approaches](#models-and-approaches)
  * [Visual Features](#visual-features)
    * [Keypoint extractor](#keypoint-extractor)
    * [Interpretation of visual features](#interpretation-of-visual-features)
  * [Audio Features](#audio-features)
    * [Feature extractor](#feature-extractor)
    * [Interpretation of audio features](#interpretation-of-audio-features)
  * [Multimodal Features](#multimodal-features)

## Datasets
<!-- Usage of the table
    Name: name of the dataset
    Year: year of publication
    Description: a short description of the dataset
    Tags: tags of the dataset e.g "audio" : :sound: , "video" : :movie_camera: , "image" : :camera:
    link: link to the dataset
    Licence: In what context is the dataset allowed to be used e.g "research only"

 -->

| Name|Year|Description|Tags|Link|Licence|
|:-|:-:|:-|:-|:-|:-:|
| Aff-Wild2 | 2022 | AffWild2 is a publicly available multimodal dataset for affect recognition and analysis, containing videos of people displaying a range of emotions and facial expressions. The dataset is split into two parts: AffWild2-Train, which includes around 1200 videos of various emotions and facial expressions, and AffWild2-Test, which consists of around 200 videos for evaluation purposes.|:camera: :movie_camera: :sound: |[ibug](https://ibug.doc.ic.ac.uk/resources/aff-wild2/)| research-only |

## Models and Approaches

### Visual Features
<!-- List of models/approaches that focus on visual input only -->
#### Keypoint extractor

|Name[Link]|Description|Tags|
|:-|:-|:-|
|[MediaPipe](https://google.github.io/mediapipe/) |MediaPipe is a framework for building multimodal applied machine learning pipelines. It provides a unified platform for the components that make up an ML pipeline, including Face Mesh,Iris Tracking,Hand Tracking, Holistic, Pose Tracking.||
|[OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)| OpenPose is a real-time multi-person keypoint detection library for body, face, hands, and foot estimation. ||
|[OpenFace](https://github.com/TadasBaltrusaitis/OpenFace)|Facial Behavorial Analysis Toolkit that allows to perform facial landmark detection, head pose estimation, facial action unit recognition, and eye-gaze estimation. ||
|[3DDFA_V2](https://github.com/cleardusk/3DDFA_V2)|3DDFA_V2 is a PyTorch implementation of 3DDFA, which is a 3D Morphable Model (3DMM) based face alignment and reconstruction framework. ||

#### Interpretation of visual features

|Name[Link]|Description|Tags|
|:-|:-|:-|
|[Facial Action Coding System](https://en.wikipedia.org/wiki/Facial_Action_Coding_System)|Movements of individual facial muscles are encoded by the FACS from slight different instant changes in facial appearance. ||

### Audio Features
<!-- List of models/approaches that focus on audio input only -->
#### Feature extractor

|Name[Link]|Description|Tags|
|:-|:-|:-|

#### Interpretation of audio features

|Name[Link]|Description|Tags|
|:-|:-|:-|

### Multimodal Features
<!-- List of models/approaches that focus on multimodal input -->
|Name[Link]|Description|Tags|
|:-|:-|:-|
