# Color-Based-Image-Retrieval-using-MATLAB

# Color-Based Image Retrieval System

## Project Overview
This project implements a **Color-Based Image Retrieval System** using MATLAB. The primary objective is to retrieve images from a dataset based on their color similarity. This is achieved through RGB histogram comparison.

## Features
- Load and process a dataset of images.
- Select a query image and compute its histogram.
- Display the top 5 matching images along with their histograms.
- Clear displayed results with a reset button.
- User-friendly GUI for easy interaction.

## Dataset
The dataset used in this project is the **Oxford 102 Flower Dataset**, which contains 102 flower categories.
- **Source:** [Kaggle - Oxford 102 Flower Dataset](https://www.kaggle.com/datasets/nunenuh/pytorch-challange-flower-dataset)
- **Dataset Size:** Approximately 330 MB.

## Requirements
- **MATLAB**: Version 2021b or higher.
- **Toolboxes**: Image Processing Toolbox.
- **Operating System**: Windows, Linux, or macOS.

## Installation and Usage
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/Color-Based-Image-Retrieval-System.git
2. Open MATLAB and navigate to the folder containing the project files.
3. Run the script colorImageRetrievalGUIClear.m to launch the GUI.
4. In the GUI:
- Load Dataset: Click to load the dataset folder containing the images.
- Select Query Image: Choose a query image from your computer to find matches.
- View Results: Observe the top five matching images and their respective RGB histograms.
- Clear Images: Reset the GUI to its default state.

