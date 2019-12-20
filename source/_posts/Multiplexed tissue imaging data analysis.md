# Multiplexed tissue imaging data analysis

<p align=center>Milk</p>
#### Note

This is a general introduction for entering the 



## Introduction to Multiplexed tissue imaging technology

Widely used tissue staining technique like Immunohistochemistry (IHC) and Immunofluorescence (IF) could only used very few markers on a sample. This limits the information we could get from precious tissue sample. Multiplexed tissue imaging technologies include Imaging mass cytometry (IMC) and Multiplexed ion beam imaging (MIBI) allow staining more than 40 antibodies on a tissue sample at the same time. Those antiboides are tagged with different metal isotopes. When using laser or ion beam to ablate a small region of tissue into plasm, it will be sent to mass cytometry to analyze the amount of corresponding ions. So that we could know the expression level of the targeted protein. Usually, the diameter of the region is 1μm or even small (down to 280 nm for IONPath tech). This gives a subcellular resolution of protein expression altas. However, the area size that can be scanned is also limited. The Hyperion system can go up to 200Hz scanning rate, this takes about 2 hours for a 1000μm*1000μm area. But a tissue sample can be much bigger than this. So, in real experiment, you will have to choose the area of interest (ROI) very carefully, usually with specific charateristics.

There are two way to analyze the data of multiplexed images, we can treat those pixels as individual pixel, or we can extract the single cell information from it. But for the current resolution in IMC, we c

## Introduction to image

### Display an image on your monitor

Images are just a series of number. 

### Digital image format

Tiff, ome.tiff, .h5

## Bio-imaging analysis toolkit

There are a lots of bio-imaging analysis toolkit, I will only introduce

If you use Python, there are lots of awasome imaging processing packages to used, you can look into the followings:

- OpenCV (Python wrapper for C++ OpenCV library)
- Scikit-image (Highly recommended)
- PIL (Python imaging library)

If you use R, there will be less choices:

- Imager

## Raw Data of acquisition

Our lab only have access to Fluidigm's Hyperion system, which is the Imaging mass cytometry system. But for IONPath or other multiplexed imaging technology, this should all be the same. 

## Cell segmentation

Here we use `ilastik` software for cell and object segmentation, it's an interactive software 

## Object segmentation

## Single cell analysis

## Spatial analysis