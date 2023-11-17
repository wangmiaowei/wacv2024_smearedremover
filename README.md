# Self-Annotated 3D Geometric Learning for Smeared Points Removal(WACV2024)

### [Project Page](https://github.com/wangmiaowei/wacv2024_smearedremover.git)  | [Paper](https://arxiv.org/abs/2311.09029) | [Data](https://github.com/wangmiaowei/wacv2024_smearedremover.git)


> [Self-Annotated 3D Geometric Learning for Smeared Points Removal](https://github.com/wangmiaowei/wacv2024_smearedremover.git)
>
> Miaowei Wang, Daniel Morris 
>
> WACV2024
> 
> Abstract: There has been significant progress in improving the accuracy and quality of consumer-level dense depth sensors. Nevertheless, there remains a common depth pixel artifact which we call smeared points. These are points not on any 3D surface and typically occur as interpolations between foreground and background objects. As they cause fictitious surfaces, these points have the potential to harm applications dependent on the depth maps. Statistical outlier removal methods fare poorly in removing these points as they tend also to remove actual surface points. Trained network-based point removal faces difficulty in obtaining sufficient annotated data. To address this, we propose a fully self-annotated method to train a smeared point removal classifier. Our approach relies on gathering 3D geometric evidence from multiple perspectives to automatically detect and annotate smeared points and valid points. To validate the effectiveness of our method, we present a new benchmark dataset: the Real Azure-Kinect dataset. Experimental results and ablation studies show that our method outperforms traditional filters and other self-annotated methods.

## Installation

## Reproducing results in the paper
## TODO List

This repository currently serves as the release of the technical paper's implementation and will undergo future updates (planned below) to enhance user-friendliness. We warmly welcome and appreciate any contributions.
- [ ] View-Norm Omega Map 
- [ ] Self-Annotated labels generation
- [ ] Self-supervised training and validation code
- [ ] Dataset for evaluation

## Bibtex

If you find the repo useful for your research, please consider citing our paper:

```
@misc{wang2023selfannotated,
      title={Self-Annotated 3D Geometric Learning for Smeared Points Removal}, 
      author={Miaowei Wang and Daniel Morris},
      year={2023},
      eprint={2311.09029},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
