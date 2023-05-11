# Groupe 4 project
Groupe 4 project of the Defragmentation Training School 2 (NEUBIAS Academy) 

_Members: Nazar Oleksiievets, Enrico Di Iuri, Thomas Lendl, Irina Belaia, Christoph Langer_
# Data
## Detailed Biological description
The sample is Zebrafish embryo 2 days post fertilization. Tail fin was removed and we are looking at the regeneration of this part. Fluorescnece signal is cytosolic GFP variant (I don't want to mention specifics here). 

## Technical Data Description
The data was acquired using single-objective lightsheet microscope (https://www.asiimaging.com/products/light-sheet-microscopy/single-objective-light-sheet/). 
Prior to the analysis the data were deskewed using pyclesperanto library (https://github.com/clEsperanto/pyclesperanto_prototype/blob/master/demo/transforms/deskew_x_test.ipynb)
Excitation source: 488 laser
Number of timepoints: 121 (We will use as many as we would be able to analyse)
Time per volume: 5 s
Voxel size: 0.354 um (We have isotropic pixel size)

### Difficulties/Challenges
The images are in a z-stack display with a 45° angle of inclination of the layers. The challenge is to obtain the segmentation of the cells in the sliced fin in order to visualize the regeneration over the time. Another problem is the penetration of the light sheet. The excitation light is absorbed and reflected by the sample leading to the degradation of fluorescence signal along propagation of the beam.

# Image Analysis Tasks
1. 3D Segmentation
2. Tracking of cell movement in 3D
3. Obtaining cytosolic fluorescence signals as a function of time for individual cells
## Biological Questions

## EDA
## Abstract Image Analysis Task Description
The task is to implement 3D segmentation and obtain integral cytosolic fluorescence signals as a function of time for individual cells.
# Failed Attempts
3D segmentation inside napari using semantic segmentation (APOC) tool.
# Solution
## Image processing
### Rotation and cropping
### Projection
## Segmentation
### Approach A
### Approach B
## Object detection
### Object labelling
### Object feature collection
## Object tracking
# References
# Presentation
