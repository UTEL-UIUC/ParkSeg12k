# ParkSeg12k: Parking Lot Segmentation Dataset

This repository contains information about **ParkSeg12k**, an open-source dataset developed for semantic segmentation of parking lots using satellite imagery. The dataset was created to address the scarcity of publicly available data for analyzing off-street parking lots in the United States.

## Key Features
- **12,617 Image-Mask Pairs**: Includes 512x512-pixel imagery, each annotated with parking lot boundaries.
- **Wide Geographic Coverage**: Covers ∼35,000 parking lots across 45 U.S. cities, totaling 297.7 km² of area and 62.5 km² of labeled parking lots.
- **Two Versions**:
  - **3-Channel RGB Dataset**: Standard satellite imagery.
  - **Near-Infrared (NIR) Channel Dataset**: Includes an additional fourth channel (NIR) corresponding to each 3-channel RGB image to enhance segmentation accuracy.
- **Data Split**: The dataset is divided into a 90%-10% train-test split.
- **Post-Processing**: Includes corrections for holes, edge simplification, and removal of misclassified roads and buildings, leading to a mean Intersection over Union (mIoU) of 84.9% and pixel-wise accuracy of 96.3% with the best model.

## Access the Dataset
The dataset is hosted on Hugging Face and can be downloaded here: 
[UTEL-UIUC/parkseg12k](huggingface.co/datasets/UTEL-UIUC/parkseg12k)

## Citation
If you use this dataset in your research, please cite the corresponding paper.

Note: This citation will be updated with the final publication details once the paper is officially published.
