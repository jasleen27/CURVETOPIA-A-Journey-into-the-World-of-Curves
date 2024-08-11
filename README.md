# CURVETOPIA-A-Journey-into-the-World-of-Curves
This project focuses on identifying, regularizing, and beautifying 2D curves. The primary objective is to develop algorithms that can transform polylines into well-defined curves, such as straight lines, circles, ellipses, rectangles, regular polygons, and star shapes. The project also explores symmetry in curves and techniques for completing incomplete curves, particularly in cases where curves have been fragmented or occluded. The end goal is to provide a comprehensive set of tools for processing and analyzing curves, making it easier to work with hand-drawn shapes and doodles.

Key Features:

Curve Regularization: Identify and regularize various shapes like circles, ellipses, rectangles, and more.
Symmetry Exploration: Detect and analyze symmetry in closed shapes using Bezier curve transformations.
Curve Completion: Complete incomplete 2D curves that have gaps or have been occluded by other shapes.

Features
Read CSV files to extract polylines.
Plot polylines using Matplotlib.
Detect geometric shapes like lines, circles, and rectangles.
Regularize shapes by completing curves using cubic splines.
Visualize symmetry in the polylines.
Tries to detect occluded figures and their position.
Export results to SVG and PNG formats.

Requirements
numpy
matplotlib
scikit-learn
scipy
svgwrite
cairosvg

*check programs till the end for corresponding outputs
