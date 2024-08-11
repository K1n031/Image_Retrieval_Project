# Image Retrieval Project

## Overview
This project is focused on developing an image retrieval system that identifies and retrieves similar images from a dataset. The system employs various image processing techniques and similarity measures to achieve efficient and accurate retrieval.

## Table of contents
* Installation
* Usage
* Project Structure
* Methodology
* Results

## Installation
### Prerequisites
Ensure you have the following packages installed:
* numpy
* PIL
* matplotlib

### Set up
1. Clone the repository
```bash
git clone https://github.com/K1n031/Image_Retrieval_Project
cd Image_Retrieval_Project
```
2. Download dataset
Use the provided script to download and unzip the dataset.
```bash
!gdown 1msLVo0g0LFmL9-qZ73vq9YEVZwbzOePF
!unzip data.zip
```

## Usage
1. Repare dataset
The dataset should be organized into a folder structure where each class of images has its own folder.
```bash
data/
├── test/
│   ├── class_1/
│   ├── class_2/
│   └── ...
├── train/
│   ├── class_1/
│   ├── class_2/
│   └── ...
```
2. Run the Project
Open the Jupyter notebook and execute the cells step by step to process the images, extract features, and perform image retrieval.
```bash
jupyter notebook Image_Retrieval_Project.ipynb
```

## Project Structure
* 'Image_Retrieval_Project.ipynb': The main notebook containing the code and explanations.
* 'data/': Directory where the image dataset is stored.
* 'requirements.txt': List of dependencies needed for the project.

## Methodology
### 1. Image Processing
* Image Resizing: All images are resized to a uniform size of 448x448 pixels.
* Feature Extraction: Custom functions are used to convert images into a numerical format suitable for comparison.

### 2. Similarity Measures
* L1 Measure (Absolute Difference): The primary metric used to compare images based on pixel differences.

### 3. Visualization
* Result Plotting: The system displays the query image alongside the top retrieved images from the dataset for visual inspection.

## Results
The system effectively retrieves similar images from the dataset, showcasing its ability to identify images with visual similarities based on the chosen metrics.
