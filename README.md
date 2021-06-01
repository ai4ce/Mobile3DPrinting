# Projector-Guided Non-Holonomic Mobile 3D Printing

Xuchu Xu, Ziteng Wang, Chen Feng

International Conference on Robotics and Automation (ICRA) 2021

[New York University Tandon School of Engineering](https://ai4ce.github.io)

## Abstract
Fused deposition modeling (FDM) using mobile robots instead of the gantry-based 3D printer enables additive manufacturing at a larger scale with higher speed. This introduces challenges including accurate localization, control of the printhead, and design of a stable mobile manipulator with low vibrations and proper degrees of freedom. We proposed and developed a low-cost non-holonomic mobile 3D printing system guided by a projector via learning-based visual servoing. It requires almost no manual calibration of the system parameters. Using a regular top-down projector without any expensive external localization device for pose feedback, this system enabled mobile robots to accurately follow pre-designed millimeter-level printing trajectories with speed control. We evaluate the system in terms of its trajectory accuracy and printing quality compared with original 3D designs. We further demonstrated the potential of this system using two such mobile robots to collaboratively print a 3D object with dimensions of 80 cm × 30 cm size, which exceeds the limitation of common desktop FDM 3D printers.

## Projector-3D Printing System 
#### Project System Setup
![System Setup](https://github.com/ai4ce/Mobile3DPrinting/blob/main/Figures/01.png)

#### Printing Robot Design
![Robot Design](https://github.com/ai4ce/Mobile3DPrinting/blob/main/Figures/02.png)

## Learning-Based Visual Servoing (LBVS)

## Experiment Results
#### Trajectory and Control Test
![exp1](https://github.com/ai4ce/Mobile3DPrinting/blob/main/Figures/05.png)
#### Single Robot Printing Test
![exp2](https://github.com/ai4ce/Mobile3DPrinting/blob/main/Figures/06.png)
![exp3](https://github.com/ai4ce/Mobile3DPrinting/blob/main/Figures/07.png)

## [Paper (arXiv)](https://arxiv.org/abs/2105.08950)
To cite our paper:
```
@inproceedings{ProjectorM3DP_ICRA_2021,
  title={Projector-Guided Non-Holonomic Mobile 3D Printing},
  author={Xu, Xuchu and Wang, Ziteng and Feng, Chen},
  booktitle={2021 IEEE International Conference on Robotics and Automation (ICRA)},
  year={2021}
}
```


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
