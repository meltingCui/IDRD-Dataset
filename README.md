# IDRD-Dataset

The Insulator Defect Recognition Dataset (IDRD) is a pixel-level annotated dataset for UAV-based insulator defect recognition, segmentation, and mask-based health indicator assessment.

## Dataset Description

IDRD contains 2304 images and 8843 annotated instances. The dataset includes three categories:
insulator: normal insulator strings
broken: broken defect regions
pollution-flashover: pollution-flashover defect regions
Pixel-level annotations are provided for insulator bodies and defect regions. Detection boxes are generated from the minimum enclosing rectangles of the annotated masks.

## Dataset Split

|      Split     | Images | Instances | Insulator | Broken | Pollution-Flashover |
| :------------: | :----: | :-------: | :-------: | :----: | :-----------------: |
|  Training set  |  2000  |    7660   |    2516   |  1600  |         3544        |
| Validation set |   144  |    561    |    171    |   108  |         282         |
|    Test set    |   160  |    622    |    193    |   154  |         275         |
|      Total     |  2304  |    8843   |    2880   |  1862  |         4101        |

## Annotation Format

The annotations are provided in pixel-level mask format. The annotation files correspond to the image files and can be used for instance segmentation, defect-region analysis, and mask-based health indicator extraction.

## Download

The dataset can be downloaded from Baidu Netdisk:
[Download IDRD Dataset](https://pan.baidu.com/s/1MrfaDBfYqiEpMgR0sOS2mA?pwd=0315)
Access code: 0315

## Usage

This dataset is intended for academic research on insulator defect recognition, pixel-level segmentation visual fault diagnosis, and health indicator assessment. Please cite this dataset or the related paper if you use IDRD in your research.

## License

This dataset is released for academic research use. Please follow the license and usage conditions provided in this repository.
