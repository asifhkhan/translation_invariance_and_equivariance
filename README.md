# Translation Invariance and Equivariance in Computer Vision

## 1. Overview

In this tutorial, we’ll explain two common concepts used in computer vision: translation invariance and translation equivariance. First, we’ll recall the mathematical definition of translation. Then we’ll explain the difference between the translation invariance and the translation equivariance by providing illustrative examples.
## 2. What Is Translation?
#### A translation is a geometric transformation that shifts all points in a given direction and by the same distance. Alternatively, it can be interpreted as sliding the origin of the coordinate system by the same amount but in the opposite direction.
The translation can be expressed mathematically as the vector sum of a constant vector <img src="https://latex.codecogs.com/svg.latex?\Large&space;\mathbf{v}" title="\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}"/> to each point <img src="https://latex.codecogs.com/svg.latex?\Large&space;\mathbf{x}" title="\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}"/>

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\mathbf{T}_v(\mathbf{x})=\mathbf{x}+\mathbf{v}" title="\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}"/>

In the following example, image (b) was obtained from image (a) by shifting each pixel 150 pixels to the left:
