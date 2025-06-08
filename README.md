# Image Manipulation Project Using OpenCV

# Project Description

This beginner-friendly Python application uses OpenCV to perform basic image manipulation — specifically, converting images to grayscale in bulk. The user provides the path to a folder containing images, and the name of a new folder where the grayscale images will be saved. The program supports common image formats (`.jpg`, `.jpeg`, `.png`), automatically creates the output folder if it doesn’t exist, and processes all valid images within the input folder efficiently.

Key features:  
- User input for flexible folder selection  
- Batch processing of images  
- Automatic output folder creation  
- Graceful handling of unreadable files  


# Tools Used
- OpenCV
- os
- pathlib

# Usage
- Run the Python script
- When prompted, enter the full path to the folder containing your images.
- Enter the name of the new folder where the processed grayscale images will be saved. If the folder doesn’t exist, it will be created automatically.
The script will process all .jpg, .jpeg, and .png images found in the input folder, convert them to grayscale, and save them in the output folder.
