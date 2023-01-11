# EDX-Data-Fitting
Energy dispersive X-ray spectrum (EDX) data are obtained using transmission electron microscopy to study the compositional information of functional layers in nano scale electronic devices. In particular, electronic devices such as transistors and memristors are consisted of multiple functional layers, resulting in several interfaces between nano-meter thick materials. To study the influence of materials distribution and diffusion at the interface, it is critical to fit the multi-peak EDX data with precise piecewise functions.

Here we built an EDX fitting APP (in Matlab) with customized Gaussian-platform piecewise functions to discover underlying parameters of the EDX data, using first-choice local search algorithms with user-defined restart. Due to different number of interfaces in the electronic devices, the EDX data usually presents different shapes (one to four peaks). Therefore, this Matlab app provides several options: 

- `One interface`: Erf (error function), Erfc (complementary error function), left Gaussian and right Gaussian 

- `Multiple interfaces`: 1 peak, 2 peaks, 3 peaks, 4 peaks

Users can choose different fitting functions according to the shape of their EDX data.
