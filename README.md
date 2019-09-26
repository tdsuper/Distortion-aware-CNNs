# Distortion-aware CNNs for Spherical Images


## Introduction
Due to the maturity of economic spherical cameras and VR head-mounted displays, the past decade has witnessed the increasing trend of spherical images being more and more easily obtained and rapidly spreaded. 

Although these images have large field-of-view, most existing deep convolutional neural networks can not be used to process these images as they have large image distortions. 

**Distortion-aware CNN**, which is initially described in "Distortion-aware CNNs for Spherical Images", is proposed to deal with this problem. It first samples the points on the tangent plane uniformly, then back-projects these points to the sphere and finds the pixels on the spherical image that should be processed by the convolution operation.

  ![image](./idea.png)
 

##Conditions of use

This package is distributed under the GNU General Public License. For information on commercial licensing, please contact the authors.

If you use this package in published work, please cite our paper as

```
@inproceedings{Distortion-aware-CNNs,
  title={Distortion-aware CNNs for Spherical Images},
  author={Zhao, Qiang and Zhu, Chen and Dai, Feng and Ma, Yike and Jin, Guoqing and Zhang, Yongdong},
  booktitle={IJCAI},
  pages={1198-1204},
  year={2018}
}
```



## Code
The code will be released recently!