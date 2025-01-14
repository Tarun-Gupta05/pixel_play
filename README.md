# Zero-Shot Image Classification with PyTorch

## Description
This project demonstrates a pipeline for zero-shot image classification using a ResNet50 model. The notebook includes steps for:
- Data preprocessing and augmentation.
- Loading and transforming datasets.
- Defining a ResNet-based model for attribute prediction.
- Training the model on predefined attribute matrices.
- Making predictions on test images and saving results in a CSV file.

## Features
- Utilizes pretrained ResNet50 for feature extraction.
- Supports GPU acceleration for efficient computation.
- Implements zero-shot inference by comparing predicted attributes to predefined class attribute matrices.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Tarun-Gupta05/pixel_play.git
   cd pixel_play
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Update the paths to your dataset and attribute files in the notebook
   ```bash
   train_dir = "/path/to/train"
   test_dir = "/path/to/test"
   predicate_matrix_file = "/path/to/predicate-matrix-continuous.txt"

   ```
   Run the notebook step-by-step to train the model and generate predictions.
   The predictions will be saved as submission.csv in the specified directory.
   
## Files and Directories
- final_notebook.ipynb: Main notebook containing the implementation.
- requirements.txt: List of Python dependencies.
- submission.csv: Example output file with predictions.
