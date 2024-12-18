# ParkSeg12k: Parking Lot Segmentation Dataset

This repository contains information about **ParkSeg12k**, an open-source dataset developed for semantic segmentation of parking lots using satellite imagery. The dataset was created to address the scarcity of publicly available data for analyzing off-street parking lots in the United States.

## Key Features
- **12,617 Image-Mask Pairs**: Includes 512x512-pixel imagery, each annotated with parking lot boundaries.
- **Wide Geographic Coverage**: Covers ∼35,000 parking lots across 45 U.S. cities, totaling 297.7 km² of area and 62.5 km² of labeled parking lots.
- **Two Versions**:
  - **3-Channel RGB Dataset**: Standard satellite imagery.
  - **Near-Infrared (NIR) Channel Dataset**: Includes an additional fourth channel (NIR) corresponding to each 3-channel RGB image to enhance segmentation accuracy.
- **Data Split**: The dataset is divided into a 90%-10% train-test split.

## Access the Dataset
The dataset is hosted on Hugging Face and can be downloaded here: 
[UTEL-UIUC/parkseg12k](https://huggingface.co/datasets/UTEL-UIUC/parkseg12k)

## Citation
If you use this dataset in your research, please cite the corresponding paper:

```bibtex
@article{qiam2024,
  title={A Pipeline and NIR-Enhanced Dataset for Parking Lot Segmentation},
  author={Shirin Qiam and Saipraneeth Devunuri and Lewis J. Lehe},
  journal={arXiv preprint arXiv:2412.13179},
  year={2024},
  url={https://arxiv.org/pdf/2412.13179}
}
```

**Note: This citation will be updated with the final publication details once the paper is officially published.**
