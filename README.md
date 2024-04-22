# ADViTUNet1


## Dataset preparation
1. Create [data] folder 
2. Download UCSD Ped2 dataset from this [website](http://www.svcl.ucsd.edu/projects/anomaly/dataset.htm) and place it in [data] folder.
3. The folder structure should look like this:
```
   | Code_official  
   |---Data  
   |-------ped1
   |---------Normal  
   |---------Abnormal
   |---------Frames
   |---------Frames_GT

```

The data folder contains the data used in this work; each folder is used or generated in stage (some samples are provided for clarification). For example :
```
-Normal: contains all the normal sequence’s frames in the dataset.
-Abnormal: contains all the abnormal sequence’s frames of the dataset.
-Frames and Frames_GT are two folders that contain the dataset’s frames with their Ground truth.
-FramesAtt: contains the generated frame’s attention map by vision transformer.
-FramesComb: contains the results frames of the combination of attention maps with their original frames.
-TrainValid: contains the data splitting into training and validation parts.
-Results: contains the results of the localization of the anomalous objects in the frames.
```
