# Ningnan Semantic Segmentation Visualization Tool Version 1.0 Documentation

## Introduction

The Ningnan Semantic Segmentation Visualization Tool is a deep learning visualization application developed using PyQt5, aimed at simplifying the experimental workflow for semantic segmentation tasks related to landslide points in the Ningnan Loess Hilly Region. The tool provides an intuitive graphical user interface (GUI), allowing users to conduct deep learning experiments without modifying the source code, thereby enhancing research efficiency.

## Version Information

- **Version**: 1.0
- **Author**: Nyongwon
- **Release Date**: November 18, 2024

## Revision History

| Date          | Version | Author    | Description      |
|---------------|---------|-----------|------------------|
| 2024-11-18    | 1.0     | Nyongwon  | Initial Release   |

## System Requirements

### Hardware Requirements

- **Storage**: 100GB or more
- **Memory**: 16GB or more
- **Processor**: Intel i5 (10th Generation) or above (with integrated graphics)
- **Graphics Card**: NVIDIA 3060 or above (optional)

### Software Requirements

- **Operating System**: Windows 10 or above, Ubuntu 20.04 or above

### Recommended Configuration

- **Processor**: AMD Ryzen 7 4800U
- **Memory**: 16GB DDR4 3200MHz
- **Graphics Card**: AMD Radeon Graphics 2GB
- **Storage**: 512GB SSD

## Tool Function Overview

### Main Page

The main page includes 10 practical buttons, each corresponding to different functions. Users can proceed with operations step by step or use specific features based on their needs.

### Image Segmentation

Clicking the "Image Segmentation" button on the main page will open a corresponding window where users can perform image segmentation tasks.

### Random Sample Selection

This feature allows users to randomly select segmented images and save them to a specified path for further processing and analysis.

### Label Creation

Users can open the labelme tool through this feature to create labels that facilitate the training of deep learning models.

### Convert Label JSON to PNG Format

This feature is used to convert created label files from JSON format to PNG format for visualization and storage purposes.

### Rule-based Data Augmentation

Users can utilize this feature to augment data to improve the model's generalization ability and robustness.

### Automatic Shuffle of Training Order and File Name Read/Write, Partitioning

This feature supports the automatic shuffling of data training order and reads file names into two files, partitioning data according to a specified ratio.

### Start Training

Users can set training parameters in this interface, which includes a sub-interface for viewing the training progress.

### Training Progress View

This interface serves as a progress display window where users can view real-time training conditions and terminate training if necessary.

### Generalization

This feature is used to extract areas that the model has learned, helping users understand the model's generalization ability.

### Data Division into 2000*2000

Users can divide images into 2000-pixel resolution segments for more detailed analysis and processing.

### Merge Partitioned Data

This feature allows users to merge segmented images into one, facilitating further processing and analysis.

## Target Users

This tool primarily targets the following user groups:

- **Students**: As a learning and experimental tool to assist students in conducting deep learning-related projects.
- **Researchers**: To provide researchers with a simplified experimental process, enhancing research efficiency.

## Tool Advantages

- **User-Friendly**: The user-friendly interface makes operations intuitive and easy to master.
- **Visual Interface**: Utilizing a visual approach for various deep learning tasks enhances user experience.
- **Compact Size**: The tool is lightweight, making it easy to download and install.
- **Strong Practicality**: Optimally designed for semantic segmentation tasks, effectively improving experimental efficiency.

## User Guide

1. **Install the Tool**: Download and install the latest version of the tool.
2. **Prepare the Runtime Environment**: Ensure that the operating system and hardware configuration meet the requirements.
3. **Launch the Tool**: Start the application and access the main page.
4. **Conduct Experiments**: Select the appropriate function based on needs and gradually conduct the experiment.

## Development Plans

Future versions will consider the following improvements:

- **Cloud Deployment**: Deploying the tool on Docker or other cloud platforms for easier accessibility.
- **Function Expansion**: Adding support for more deep learning models to enhance the tool's versatility.
- **Interface Optimization**: Further optimizing the layout and interaction design of the interface based on user feedback.

## Conclusion

Thank you for using the Ningnan Semantic Segmentation Visualization Tool. If you encounter any issues or have suggestions during use, please provide feedback through GitHub. We are committed to continuously improving the tool to meet user needs.

For more information, please refer to the official documentation and GitHub page of the tool.
