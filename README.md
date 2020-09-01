# The list of visual SLAM and visual odometry methods

This memo is organized for personal use.

## Index
* [Projects](#projects)
* [Datasets](#datasets)

## Projects

| Title | Paper | Method | Input | SLAM or VO | Localization | Loop close | Year | Source Code |
|-|-|-|-|-|-|-|-|-|
| PTAM | [Paper](https://ieeexplore.ieee.org/document/4538852) | feature | mono | SLAM | yes | | 2007 | [github](https://github.com/Oxford-PTAM/PTAM-GPL) |
| LSD-SLAM | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-10605-2_54) | direct | mono, stereo | SLAM | | yes | 2013 | [github](https://github.com/tum-vision/lsd_slam) |
| SVO | [Paper](https://ieeexplore.ieee.org/document/6906584) | direct | mono | VO | | | 2014 | [github](https://github.com/uzh-rpg/rpg_svo) |
| SVO 2.0 | [Paper](https://ieeexplore.ieee.org/document/7782863) | direct | mono, stereo, fisheye | VO | | | 2016 | [github](https://github.com/symao/svo2) |
| PL-SVO | [Paper](https://ieeexplore.ieee.org/document/7759620) | feature, direct | mono | VO | | | 2016 | [github](https://github.com/rubengooj/pl-svo) |
| ORB-SLAM | [Paper](https://ieeexplore.ieee.org/document/7219438) | feature | mono | SLAM | yes | yes | 2015 | [github](https://github.com/raulmur/ORB_SLAM) |
| ORB-SLAM2 | [Paper](https://ieeexplore.ieee.org/document/7946260) | feature | mono, stereo, rgb-d | SLAM | yes | yes | 2017 | [github](https://github.com/raulmur/ORB_SLAM2) |
| ORB-SLAM3 | [Paper](https://arxiv.org/abs/2007.11898) | feature | mono, mono-imu, stereo, stereo-imu, rgb-d, rgb-d-imu, fisheye | SLAM | yes | yes | 2020 | [github](https://github.com/UZ-SLAMLab/ORB_SLAM3) |
| DSO | [Paper](https://ieeexplore.ieee.org/document/7898369) | direct | mono | VO | | | 2017 | [github](https://github.com/JakobEngel/dso) |
| Stereo DSO | [Paper](https://arxiv.org/abs/1708.07878) | direct | stereo | VO | | | 2017 | |
| Omnidirectional DSO | [Paper]() | direct | fisheye | VO | | | 2018 | [github]() |
| LDSO | [Paper](https://arxiv.org/abs/1808.01111) | direct | mono | VO | | yes | 2018 | [github](https://github.com/tum-vision/LDSO) |
| VI-DSO | [Paper](https://arxiv.org/abs/1804.05625) | direct | mono-imu | VO | | | 2018 | |
| VINS-fusion | [Paper](https://ieeexplore.ieee.org/document/8421746) | shi tomasi + KLT | stereo, mono-imu, stereo-imu, fisheye | VO | yes | yes | 2018 | [github](https://github.com/HKUST-Aerial-Robotics/VINS-Fusion) |
| MSCKF |
| OKVIS |
| ROVIO |
| BASALT |
| Kimera | [Paper](https://arxiv.org/abs/1910.02490) | shi tomasi + KLT | stereo-imu | VO | | yes | 2020 | [github](https://github.com/MIT-SPARK/Kimera) |
| UcoSLAM | [Paper](https://arxiv.org/abs/1902.03729) | feature, marker | mono, stereo, rgb-d | SLAM | yes | yes | 2019 | [website](http://ucoslam.com/) |
| TagSLAM | [Paper](https://arxiv.org/abs/1910.00679) | marker | | SLAM | yes | yes | 2019 | [github](https://github.com/berndpfrommer/tagslam) |
| ORB-YGZ-SLAM | | feature, direct | mono | SLAM | | yes | | [github](https://github.com/gaoxiang12/ORB-YGZ-SLAM) |
| LCSD-SLAM | [Paper](https://arxiv.org/abs/1807.10073) | feature, direct | mono | SLAM | | yes | 2018 | [github](https://github.com/sunghoon031/LCSD_SLAM) |
| DXSLAM | [paper](https://arxiv.org/abs/2008.05416) | feature(ORB-SLAM2, SuperPoint, NetVlad) | | SLAM | | | 2020 | [github](https://github.com/ivipsourcecode/dxslam) |
| PL-SLAM | [paper](https://ieeexplore.ieee.org/abstract/document/8680013) | feature | stereo | SLAM | | yes | 2019 | [github](https://github.com/rubengooj/pl-slam) |
| Structure-SLAM | [paper](https://arxiv.org/abs/2008.01963) | feature | mono | SLAM | | yes | 2020 | [github](https://github.com/yanyan-li/Structure-SLAM-PointLine) |

To do...
- input: stereo, rgb-d, inertial, fishehe camera
- feature(point, line, ...), direct, ...
- deep learning based

## Datasets
| Title | Paper | Year | datasets |
|-|-|-|-|
| EuRoC MAV Dataset | | 2016 | [datasets](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets) |
| TUM-Mono | | 2016 | [datasets](https://vision.in.tum.de/data/datasets/mono-dataset) |
| TUM-RGBD | | 2012 | [datasets](https://vision.in.tum.de/data/datasets/rgbd-dataset) |
| TUM-Visual-Inertial | | 2018 | [datasets](https://vision.in.tum.de/data/datasets/visual-inertial-dataset) |
| KITTI | | 2013 | [datasets](http://www.cvlibs.net/datasets/kitti/index.php) |
| ICL-NUIM | | 2014 | [datasets](https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html) |
