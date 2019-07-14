# GradientPicker

## Description

Gradientpicker allows you to capture the primary desktop and create a gradient by dragging the mouse over the captured image.

## Background

I wanted to create gradients for colorizing a Canyon I created using [World Creator](https://www.world-creator.com/). With this tool you can load an image of a mountain, drag a line along the mountain and get the color gradient of it.

## Usage

The app captures the primary desktop and puts it as image into the Source Image panel. When you drag the mouse over the image a line is painted. All points along the line are sampled and a gradient is created from it. When you paint a new line, the existing one and its gradient are erased and a new one is created.

You can change the gradient width by choosing the desired resolution.

The gradient can be saved as PNG file with the width of the gradient and a height of 1 pixel.

If you want to capture another image, clicking "New Session" captures the primary desktop again.

## Screenshot

Here's a screenshot how it looks like currently:

![gradient-picker-screenshot](https://user-images.githubusercontent.com/10963432/61181765-c0809400-a62a-11e9-8b4f-5adc67676f2b.jpg)

The black line is the line of which the gradient points are sampled.

And here's a video of it in action:

[![GradientPicker](https://img.youtube.com/vi/lhgxTnwMreg/0.jpg)](https://www.youtube.com/watch?v=lhgxTnwMreg)


## Example Use Case

Here's how the gradient is used on a [World Creator](https://www.world-creator.com/) terrain:

![canyon](https://user-images.githubusercontent.com/10963432/61181820-819f0e00-a62b-11e9-9bf2-25c9fe3ae0b3.jpg)


## Build

The pre-compiled executable is compiled for Win10 x64 and provided for convenience. 

Usage is of course at your own risk, unfortunately I don't have the means to sign the app. But feel free to compile the source on your own.

## License

[MIT License](https://github.com/Roland09/GradientPicker/blob/master/LICENSE)

## Credits

This is my first C# standalone app, it only took 4 hours to figure out how to do this thanks to the awesome people who provided support in these links:

- https://www.codeproject.com/Articles/485883/Create-your-own-Snipping-Tool
- https://stackoverflow.com/questions/7822514/multi-color-linear-gradient-in-winforms
- https://rosettacode.org/wiki/Bitmap/Bresenham%27s_line_algorithm#C.23



