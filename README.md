# Etiologic  Classification of Macular Edema Using a Deep Learning Approach in Optical Coherence Tomography Scans dataset
This repository contains images from Etiologic Classification of Macular Edema Using a Deep Learning Approach in Optical Coherence Tomography Scans paper.

## Scans classification

For scans classification two approaches were ttaken into account first multiclassification and sencondly binary classification.

### Binary Classification

For binary classification, in folder splited can be found images in its original size and in folder reshapedSplited images reshaped to 256*256 
can be found both folders contains images for:

- AMD
- DME
- RVO

Each of those folder has got images divided into:

- Train
- Test
- Validation

### MultiClassification

 For images multiclassification between all diseases there are two folders available: splitedMulticlass and reshapedSplitedMulticlass, 
 last folder contains all images resized into 256 * 256, and in both divided among training, test and validation sets for:
 
 - Control
 - DME
 - AMD
 - RVO
 
 ## Scans segmentation
 
 For image segmentation mask for biomarkers suchs as fluids, focis, cyst and drusen are available, divided as:
 
 - oftalmoCystSegmentationImgs (Cysts)
 - oftalmoDrusenSegmentationImgs (Drusen)
 - oftalmoFluidsSegmentationImgs (Intraretinal and subretinal Fluids)
 - oftalmoFocisSegmentationImgs (Hyperreflective Focis)
 
 On each folder two folder with real shape images an reshaped images into 256 * 256 are found those are splited and reshapedSplited, 
 each of those folder has got a folder for segmented images performed by expert ophthalmologist (mask) and oct scans ground truth (images), 
 further dividing each folder into training, test and validation each image and its respective mask can be distinguished by its name.

## Citing this work

If you find this information or this repository useful in your research, please consider citing:

    
