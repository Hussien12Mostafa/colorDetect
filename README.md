# Color Detection Using OpenCV and Pandas
This repository contains a Python script that allows you to detect the name of a color in an image by double-clicking on a pixel. It uses OpenCV and Pandas to read a CSV file containing color information and then matches the pixel's RGB values to the closest color in the CSV data.

# Getting Started
To use this script, you need to have Python installed on your system along with the OpenCV and Pandas libraries. You can install the required packages using pip:


pip install opencv-python-headless
pip install pandas
# Usage

Replace the img_path variable with the path to your image file.

Make sure you have a CSV file named colors.csv in the same directory, containing color information with columns: "color," "color_name," "hex," "R," "G," "B."



Example
Here's how the script works:

You open an image by specifying its path.
Click on a pixel in the image, and it will display the color name and RGB values of that pixel.
# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
The color data used in this script is provided in the colors.csv file.
This script is a simple example of color detection using OpenCV and Pandas.
Feel free to use and modify this code for your own projects!
