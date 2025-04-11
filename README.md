# Activity Recognition in Smart Homes

## Introduction
This repository includes the PyTorch implementation of the "Activity Recognition in Smart Homes with Knowledge Graph and Attention Guided Learning" framework [1]. This paper has been accepted in CVIP2024 Conference. The framework is built on multiple datasets. We test the framework using publicly available benchmarks like Toyota Smarthome [2], and MPII Cooking 2 [3].

## Datasets
#### Toyota Smarthome
The Toyota Smarthome dataset [2] consists of real-world activities performed by humans in their daily lives, such as reading, breakfast, and so on. The dataset is collected across three different scenes: the dining room, living room, and kitchen. The dataset includes 16,115 videos of 31 action classes. The videos are captured from 7 different camera perspectives. It also contains 3 composite activities. The videos have resolution of 640 × 480 and offers 3 modalities: RGB, Depth and 3D skeleton. For privacy, the face of the subjects is blurred using tinyface detection method.

#### MPII Cooking 2
The dataset contains videos of cooking activities. Rohrbach et al. [3] presented the MPII Cooking 2 dataset to address the issue of fine-grained actions and composite activities in a kitchen scenario. The dataset includes 273 videos. It contains fine-grained actions, such as, ‘cut dice’, ‘take lid’, and ‘put lid’, and so on. Additionally, it has 59 composite activities. The number of actors is 30. The dataset is separated into train and test groups according to subject. The train set includes 24 videos of different subjects, with the remaining 6 used for testing.

## Code
The code and model will be available soon...

## References
1. S. Kumbhare, A. Chowdhury, "Activity recognition in smart homes with knowledge graph and attention-guided learning," In: Proc. Int. Conf. Comput. Vis. Image Proc. (CVIP) (Accepted). pp. 1–14, Springer 2024.
2. S. Das, R. Dai, M. Koperski, L. Minciullo, L. Garattoni, F. Bremond, G. Francesca, "Toyota smarthome: Real-world activities of daily living," In: Proc. IEEE Int. Conf. Comput. Vis. pp. 833–842, 2019.
3. M. Rohrbach, A. Rohrbach, M. Regneri, S. Amin, M. Andriluka, M. Pinkal, B. Schiele, "Recognizing fine-grained and composite activities using hand-centric features and script data," In: Int. J. Comput. Vis. 119, pp. 346-373, 2016.
