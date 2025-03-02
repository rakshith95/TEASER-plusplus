# TEASER++: fast & certifiable 3D registration 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Documentation Status](https://readthedocs.org/projects/teaser/badge/?version=latest)](https://teaser.readthedocs.io/en/latest/?badge=latest)
[<img src="https://github.com/MIT-SPARK/TEASER-plusplus/workflows/build/badge.svg">](https://github.com/MIT-SPARK/TEASER-plusplus/actions)

![TEASER++ 3DSmooth](examples/teaser_python_3dsmooth/3dsmooth_example.gif)

TEASER++ is a fast and certifiably-robust point cloud registration library written in C++, with Python and MATLAB bindings.

## About
![](doc/banner.png)
*Left: correspondences generated by [3DSmoothNet](https://github.com/zgojcic/3DSmoothNet) (green and red lines represent the inlier and outlier correspondences according to the ground truth respectively). Right: alignment estimated by TEASER++ (green dots represent inliers found by TEASER++).*

TEASER++ can solve the rigid body transformation problem between two point clouds in 3D. It performs well even if the input correspondences have an extremely large number of outliers. For a short conceptual introduction, check out our [video](https://www.youtube.com/watch?v=xib1RSUoeeQ). For more information, please refer to our papers:
- [H. Yang](http://hankyang.mit.edu/), [J. Shi](http://jingnanshi.com/), and [L. Carlone](http://lucacarlone.mit.edu/), "TEASER: Fast and Certifiable Point Cloud Registration,". [arXiv:2001.07715](https://arxiv.org/abs/2001.07715) [cs, math], Jan. 2020. ([pdf](https://arxiv.org/pdf/2001.07715.pdf))
- [H. Yang](http://hankyang.mit.edu/) and [L. Carlone](http://lucacarlone.mit.edu/), “A Polynomial-time Solution for Robust Registration with Extreme Outlier Rates,” in Robotics: Science and Systems (RSS), 2019. ([pdf](https://arxiv.org/pdf/1903.08588.pdf))

If you find this library helpful or use it in your projects, please cite:
```bibtex
@article{Yang20tro-teaser,
  title={{TEASER: Fast and Certifiable Point Cloud Registration}},
  author={H. Yang and J. Shi and L. Carlone},
  journal={{IEEE} Trans. Robotics},
  pdf={https://arxiv.org/pdf/2001.07715.pdf},
  Year = {2020} 
}
```

If you are interested in more works from us, please visit our lab page [here](http://web.mit.edu/sparklab/).

## Getting Started
- Installation
  - [Dependencies](https://teaser.readthedocs.io/en/latest/installation.html#installing-dependencies)
  - [Compilation](https://teaser.readthedocs.io/en/latest/installation.html#compilation-and-installation)
  - [Install C++ Libraries](https://teaser.readthedocs.io/en/latest/installation.html#installing-c-libraries-and-headers)
  - [Install Python Bindings](https://teaser.readthedocs.io/en/latest/installation.html#installing-python-bindings)
  - [Install MATLAB Bindings](https://teaser.readthedocs.io/en/latest/installation.html#installing-matlab-bindings)
  - [Run Tests](https://teaser.readthedocs.io/en/latest/installation.html#run-tests)
- Usage
  - [In C++](https://teaser.readthedocs.io/en/latest/quickstart.html#usage-in-c-projects)
  - [In Python](https://teaser.readthedocs.io/en/latest/quickstart.html#usage-in-python-projects)
  - [In MATLAB](https://teaser.readthedocs.io/en/latest/quickstart.html#usage-in-matlab-projects)
  - [In ROS](https://teaser.readthedocs.io/en/latest/quickstart.html#usage-in-ros-projects)
- API Documentation
  - [C++](https://teaser.readthedocs.io/en/latest/api-cpp.html)
  - [Python](https://teaser.readthedocs.io/en/latest/api-python.html)
  - [MATLAB](https://teaser.readthedocs.io/en/latest/api-matlab.html)

## Other Publications
Other publications related to TEASER include:
- [H. Yang](http://hankyang.mit.edu/) and [L. Carlone](http://lucacarlone.mit.edu/), “A quaternion-based certifiably optimal solution to the Wahba problem with outliers,” in Proceedings of the IEEE International Conference on Computer Vision (ICCV), 2019, pp. 1665–1674. ([pdf](https://arxiv.org/pdf/1905.12536.pdf))
- [H. Yang](http://hankyang.mit.edu/), [P. Antonante](http://www.mit.edu/~antonap/), [V. Tzoumas](https://vasileiostzoumas.com/), and [L. Carlone](http://lucacarlone.mit.edu/), “Graduated Non-Convexity for Robust Spatial Perception: From Non-Minimal Solvers to Global Outlier Rejection,” IEEE Robotics and Automation Letters (RA-L), 2020. ([pdf](https://arxiv.org/pdf/1909.08605))

## Acknowledgements
This work was partially funded by ARL DCIST CRA W911NF-17-2-0181, ONR RAIDER N00014-18-1-2828, Lincoln Laboratory “Resilient Perception in Degraded Environments”, and the Google Daydream Research Program.
