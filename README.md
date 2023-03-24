<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

# Affective Computing Knowledge Exchange
<!-- write a short introduction -->
This repository is a collection of datasets, models and approaches for affective computing. The goal is to provide a comprehensive overview of the current state of the art in the field of multimodal affect computing with a focus on emotion extraction from different modalities. The repository is structured as follows:

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#datasets">Datasets</a></li>
    <li>
      <a href="#models-and-approaches">Models and Approaches</a>
      <ul>
        <li>
          <a href="#visual-features">Visual Features</a>
          <ul>
            <li><a href="#keypoint-extractor">Keypoint extractor</a></li>
            <li><a href="#interpretation-of-visual-features">Interpretation of visual features</a></li>
          </ul>
        </li>
        <li>
          <a href="#audio-features">Audio Features</a>
          <ul>
            <li><a href="#feature-extractor">Feature extractor</a></li>
            <li><a href="#interpretation-of-audio-features">Interpretation of audio features</a></li>
          </ul>
        </li>
        <li><a href="#multimodal-features">Multimodal Features</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>

  </ol>
</details>


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

<p align="right">[<a href="#readme-top">back to top</a>]</p>

## Models and Approaches
<p align="right">[<a href="#readme-top">back to top</a>]</p>

### Visual Features
<!-- List of models/approaches that focus on visual input only -->
<p align="right">[<a href="#readme-top">back to top</a>]</p>

#### Keypoint extractor

|Name[Link]|Description|Tags|
|:-|:-|:-|
|[MediaPipe](https://google.github.io/mediapipe/) |MediaPipe is a framework for building multimodal applied machine learning pipelines. It provides a unified platform for the components that make up an ML pipeline, including Face Mesh,Iris Tracking,Hand Tracking, Holistic, Pose Tracking.||
|[OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)| OpenPose is a real-time multi-person keypoint detection library for body, face, hands, and foot estimation. ||
|[OpenFace](https://github.com/TadasBaltrusaitis/OpenFace)|Facial Behavorial Analysis Toolkit that allows to perform facial landmark detection, head pose estimation, facial action unit recognition, and eye-gaze estimation. ||
|[3DDFA_V2](https://github.com/cleardusk/3DDFA_V2)|3DDFA_V2 is a PyTorch implementation of 3DDFA, which is a 3D Morphable Model (3DMM) based face alignment and reconstruction framework. ||

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Interpretation of visual features

|Name[Link]|Description|Tags|
|:-|:-|:-|
|[Facial Action Coding System](https://en.wikipedia.org/wiki/Facial_Action_Coding_System)|Movements of individual facial muscles are encoded by the FACS from slight different instant changes in facial appearance. ||

<p align="right">[<a href="#readme-top">back to top</a>]</p>

### Audio Features
<!-- List of models/approaches that focus on audio input only -->
<p align="right">[<a href="#readme-top">back to top</a>]</p>

#### Feature extractor

|Name[Link]|Description|Tags|
|:-|:-|:-|
<p align="right">[<a href="#readme-top">back to top</a>]</p>

#### Interpretation of audio features

|Name[Link]|Description|Tags|
|:-|:-|:-|
<p align="right">[<a href="#readme-top">back to top</a>]</p>

### Multimodal Features
<!-- List of models/approaches that focus on multimodal input -->
|Name[Link]|Description|Tags|
|:-|:-|:-|
<p align="right">[<a href="#readme-top">back to top</a>]</p>

## Contact
<!-- List of people who contributed to this Knowledge Exchange Repository -->
* [Stella Grasshof](https://pure.itu.dk/en/persons/stella-grasshof) - IT University of Copenhagen
* [Simon Leminen Madsen](https://github.com/leminen) - Alexandra Institute
* [Eike Kutzki](https://github.com/eikekutz) - Alexandra Institute

<p align="right">[<a href="#readme-top">back to top</a>]</p>

## Acknowledgements
<!-- List of people who contributed to this Knowledge Exchange Repository -->
*
*
*
*

<p align="right">[<a href="#readme-top">back to top</a>]</p>




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/alexandrainst/AffectiveComputingKnowledgeExchange/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/alexandrainst/AffectiveComputingKnowledgeExchange/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/alexandrainst/AffectiveComputingKnowledgeExchange/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/alexandrainst/AffectiveComputingKnowledgeExchange/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/alexandrainst/AffectiveComputingKnowledgeExchange/blob/master/LICENSE.txt
