# Color-Based-Image-Retrieval-using-MATLAB
## Project Title
Color-Based Image Retrieval System (CBIRS)

## Team Member
- **Naga Prem Sai Nellure**

## Abstract
This project presents the **Color-Based Image Retrieval System (CBIRS)** implemented in MATLAB, designed to retrieve images from a dataset based on their color composition. The system utilizes a **Graphical User Interface (GUI)**, enabling users to query images by selecting a reference image. RGB histograms are calculated for image matching. This project demonstrates practical applications of image processing in areas such as digital asset management and media libraries.


## Features
1. **Dataset Loader:** Load a dataset of images for analysis.
2. **Query Selection:** Users can select a query image to retrieve similar images based on color similarity.
3. **Image Matching:** Displays the top five matches for the query image alongside their RGB histograms.
4. **Clear Option:** Allows users to reset the interface.
5. **RGB Histogram Comparison**: Used for image similarity measurements.
6. **Simple GUI**: User-friendly interface for intuitive interaction.

## Dataset
The dataset used in this project is the **Oxford 102 Flower Dataset**, which contains 102 flower categories.
- **Source:** [Kaggle - Oxford 102 Flower Dataset](https://www.kaggle.com/datasets/nunenuh/pytorch-challange-flower-dataset)
- **Dataset Size:** Approximately 330 MB.
- **Contents:** 8,189 images across 207 folders with diverse floral compositions.

## Requirements
- **MATLAB**: Version 2021b or higher, MATLAB App Designer for GUI development
- **Toolboxes**: Image Processing Toolbox.
- **Operating System**: Windows.

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


## Format and Size of Input Images
- The system processes images in .jpg format.
- Images are resized to 224x224 pixels for consistent histogram calculations.


## Code Overview
The project includes the following key files:
- colorImageRetrievalGUIClear.m: Main script to launch the GUI.
- loadDataset.m: Loads and processes the dataset by calculating histograms and RGB averages.
- TestRGBModel.m: Script to calculate RGB histograms for individual images.
- Folder: dataset - Contains the images used for matching.

## Output
The GUI displays:
1. Query Image: The selected image by the user.
2. Top 5 Matches: Images most similar to the query image based on RGB histogram comparison.
3. RGB Histograms: Visual representation of the color composition for the query and matched images.

Below are some example outputs of the GUI after executing the project:

#### GUI Window 
![CBIRS Output 1](CBIRS%20Output%201.png)

#### Clear Window State
![Clear Window Output](CBIRS%20Output%201%20Clear%20window.png)

#### Query and Matches Display
![CBIR Output 2](CBIR%20Output%202.png)
![CBIR Output 3](CBIR%20Output%203.png)
![CBIR Output 4](CBIR%20Output%204.png)
![CBIR Output 5](CBIR%20Output%205.png)

