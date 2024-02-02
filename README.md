# *WhiteBoard-Application*
A simple whiteboard application built using Tkinter in Python.

## Table of Contents
• Description

• Features

• Methods Covered

• Usage

• Screenshots

## Description

The Whiteboard application is a basic drawing tool developed using Tkinter, the standard GUI toolkit for Python. It allows users to draw lines on a canvas, change the drawing color, clear the canvas, and insert images. The application provides a user-friendly interface with a color palette and slider for line width control.

## Features:

### • Drawing:
Use the left mouse button to draw lines on the canvas.

### • Color Palette: 
Select different colors from the displayed palette.

### • Eraser: 
Clear the entire canvas with the eraser tool.

### • Image Insertion: 
Insert images onto the canvas and drag them around.

### • Line Width Slider: 
Adjust the width of the drawing lines using the slider.

## Methods Covered:

	Drawing Methods:

•	locate_xy(work): Update current coordinates based on mouse position.

•	addline(work): Draw lines on the canvas based on current and previous coordinates.

	Color Management:

•	show_color(new_color): Update drawing color.

	Canvas Actions:

•	new_canvas(): Clear the canvas.

•	insertimage(): Insert an image onto the canvas.

•	my_callback(event): Callback for dragging an image on the canvas.

	Slider Handling:

•	get_current_value(): Get the current value of the slider.

•	slider_changed(event): Update the label with the current slider value.

## Usage:

• Upon launching the application, a canvas and color palette will be displayed.

• Select a color from the palette.

• Use the left mouse button to draw lines on the canvas.

• Adjust the line width with the slider.

• Clear the canvas using the eraser tool.

• Insert images onto the canvas and drag them around.

## Screenshots:

![image](https://github.com/Amrisha7/WhiteBoard-Application/assets/136724257/092dace1-36e9-4938-9b44-387b537d48ff)
