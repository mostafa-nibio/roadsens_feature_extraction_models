## RoadSens model for segmenting the visible surface of forest roads

This repository contains the trained model for the RoadSens platform. The model detects and segments the road surface from stereo camera footage. It is a semantic segmentation tool to create binary masks that distinguish the road from the surrounding environment in each video frame. The processed output from YOLOv8 can then be used to segment the 3D point clouds retrieved from the stereo camera. The open-access paper describing the RoadSens platform can be found [here](https://doi.org/10.1016/j.compag.2024.109710).

## Licensing
The road segmentation model in this repository is a YOLOv8 model by Ultralytics, which is licensed under the AGPL-3.0. You can find the license [here](https://firebasestorage.googleapis.com/v0/b/ultralytics-public-site.appspot.com/o/license%2FAGPL-3.0-Software-License.pdf?alt=media).

For the original YOLOv8 source code, visit [Ultralytics YOLOv8 Repository](https://github.com/ultralytics/ultralytics).

