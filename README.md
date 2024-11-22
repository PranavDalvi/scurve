# This repo was forked to make changes to the code for my MSc C.S research project Malware-Detection-System-Using-Machine-Learning-and-Binary-Visualization

- To install it on your system:
1. Download the repo (unzip if downloaded as zip)
2. cd in to the repo and run `pip install .`
3. Make sure you have installed gcc, cmake, libcairo2-dev, pkg-config and python3-dev for linux (build-essential for ubuntu)

- Run example
```bash
binvis -c class -m hilbert -s 256 -t unrolled input.file output.png
```

## Thank you Aldo Cortesi for creating this amazing tool

A collection of algorithms and visualisation tools related to space-filling
curves.

# See [binvis.io](http://binvis.io) for my more recent interactive binary visualisation tool

# The Curves 

The following traversals of all points in a space are supported (some are true
space-filling curves, some are not):
    
- __hilbert__:    Hilbert curve
- __natural__:    A natural-order traversal of all points, where each co-ordinate is simply treated as a digit.
- __zigzag__:     A traversal of all points that zig-zags to ensure that each point differs from the previous point by a unit-offset in only one dimension.
- __zorder__:     Z-order curve

# The Tools 

- __binvis__: Visualize binaries using space-filling curves.  
- __colorswatch__: Creates a swatch with a visual breakdown of the colours
contained in a specified image.
- __cube__: Outputs a POV-Ray definition file for drawing 3-dimensional curves.
- __drawcurve__: Generates two dimensional lines-and-vertexes drawings of
space-filling curves.
- __gray__: Prints a bit representation of the Gray codes of a specified bit
width.
- __testpattern__: Projects a 3-dimensional traversal of the RGB colour cube onto
a specified two-dimensional curve.


# More info

Development on Scurve is usually spurred along by posts on my blog. Some of
scurve's features are documented and illustrated in the following posts:

- [Portrait of the Hilbert Curve](http://corte.si/posts/code/hilbert/portrait/index.html) 
- [Generating colour maps with space-filling curves](http://corte.si/posts/code/hilbert/swatches/index.html)
- [Hilbert Curve + Sorting Algorithms + Procrastination = ?](http://corte.si/posts/code/sortvis-fruitsalad/index.html)
