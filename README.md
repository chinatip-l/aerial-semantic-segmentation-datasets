# Improved Semantic Segmentation of Aerial Imagery

## Description

This dataset is an enhanced version of the original "Semantic Segmentation of Aerial Imagery" dataset by Humans in the Loop. The improvements include cropping, layer splitting, and other enhancements to improve the dataset's usability for various machine learning and computer vision applications.

## Original Dataset

- **Title**: Semantic Segmentation of Aerial Imagery
- **Authors**: Humans in the Loop
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery)
- **License**: Creative Commons Attribution 4.0 International (CC BY 4.0)
- **Description**: The dataset consists of satellite images of Dubai, the UAE, segmented into six classes, including buildings, roads, and vegetation.

## Improvements

1. **Cropping**: Images have been cropped to 128x128 pixels, both for the original images and their corresponding masks, making them suitable for training small models.
2. **Split Masks**: The original masks were RGB images with different colours representing different classes. In this improved version, masks have been split into separate images for each class, organised into dedicated folders for easier access and processing.

## Dataset Structure

The dataset is organised as follows:
```
aerial-semantic-segmentation-datasets/
├── images/
│ ├── im_000000.png
│ └── ...
├── masks/
│ ├── BUILDING/
│ │ ├── msk_000000.png
│ │ └── ...
│ ├── ROAD/
│ │ ├── msk_000000.png
│ │ └── ...
│ └── ...
├── README.md
└── LICENSE.txt
```

## Usage

To use this dataset, download the files and follow the structure outlined above. Each image in the `images` directory has corresponding mask files in the appropriate class directories within the `masks` folder.

## License

This dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0). You are free to:

- **Share**: Copy and redistribute the material in any medium or format.
- **Adapt**: Remix, transform, and build upon the material for any purpose, even commercially.

## Contact

For any questions or issues, please contact me at l.chinatip@gmail.com.

