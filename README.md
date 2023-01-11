# STEM EDX Data Fitting
Energy dispersive X-ray spectrum (EDX) data are obtained using (scanning) transmission electron microscopy (STEM) to study the compositional information of functional layers in nano scale electronic devices. In particular, electronic devices such as transistors and memristors are consisted of multiple functional layers, resulting in several interfaces between nano-meter thick materials. To study the influence of materials distribution and diffusion at the interface, it is critical to fit the multi-peak EDX data with precise piecewise functions.

Here we built an EDX fitting APP (in Matlab) with customized Gaussian-platform piecewise functions to discover underlying parameters of the EDX data, using first-choice local search algorithms with user-defined restart. Due to different number of interfaces in the electronic devices, the EDX data usually presents different shapes (one to four peaks, sometimes with platform functions). Therefore, this Matlab app provides several options: 

- `One interface`: Erf (error function), Erfc (complementary error function), left Gaussian and right Gaussian 

- `Multiple interfaces`: 1 peak, 2 peaks, 3 peaks, 4 peaks

Users can choose different fitting functions according to the shape of their EDX data.

## Installation
To install this app in your matlab:
<br />1, Make sure that the Matlab - `Curve Fitting Toolbox`[![matlab_logo2](https://user-images.githubusercontent.com/101215307/211877316-550998f5-e5bc-4ab3-8b8f-b9a2f3d64949.png)](https://www.mathworks.com/products/curvefitting.html) is already installed. 
<br />2, Copy the STEM EDX Fitting.mlappinstall file to your current working folder in MATLAB. 
<br />3, Right click on the file and select ‘Install’.

## Usage
Users need to put initial starting points for parameters of their EDX data. For examples, the parameters (c, w, h, &#963;1, &#963;2) for every peak are defined in the following images.


