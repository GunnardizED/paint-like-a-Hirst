Color Dot Painting

This Python script generates a painting of colorful dots using the turtle module. The script extracts colors from an image using the colorgram library and then uses those colors to create a dot painting on the screen.

Prerequisites

    Python 3.x
    turtle module
    colorgram library

Installation

    Make sure you have Python 3.x installed on your system.
    Install the colorgram library by running the following command:

    pip install colorgram.py

    Save the script to a file with a .py extension (e.g., color_dot_painting.py).

Usage

    Prepare an image file (pic.jpg) that contains the colors you want to use for the dot painting.
    Save the image file in the same directory as the script.
    Run the script using the following command:

    python color_dot_painting.py

    A turtle graphics window will appear.
    The script will extract colors from the image file using the colorgram library and store them in the color_list.
    The turtle will then paint a series of dots on the screen using the colors from the color_list.
    The dots will be arranged in a grid pattern, with each row containing 10 dots.
    After all dots are painted, you can close the window by clicking on it.

Customization

You can customize the following aspects of the Color Dot Painting:

    Image: Replace pic.jpg with your own image file in the colorgram.extract() line to extract colors from a different image.
    Color List: Modify the color_list variable to include your own RGB color values. You can remove or add colors as desired.
    Dot Size: Adjust the dot size by changing the first argument in the tim.dot() line. Larger values will create bigger dots.
    Dot Spacing: Modify the distance that the turtle moves forward after each dot is painted by changing the argument in the tim.forward() line.
    Grid Pattern: Customize the grid pattern by changing the values in the if dot_count % 10 == 0 block. Adjust the angles and distances to create different patterns.
