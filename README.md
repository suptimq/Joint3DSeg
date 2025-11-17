# Joint 3D Point Cloud Segmentation using Real-Sim Loop: From Panels to Trees and Branches

### This work is now accepted at ICRA 2025.

## Overview

In this study, we proposed a novel approach that incorporated a Real2Sim L-TreeGen for training data generation and a joint model (J-P2TB) designed for the P2TB task. The J-P2TB model, trained on the generated simulation dataset, was used for joint segmentation of real-world panel point clouds via zero-shot learning. Compared to representative methods, our model outperformed them in most segmentation metrics while using 40\% fewer learnable parameters. This Sim2Real result highlighted the efficacy of L-TreeGen in model training and the performance of J-P2TB for joint segmentation, demonstrating its strong accuracy, efficiency, and generalizability for real-world applications. These improvements would not only greatly benefit the development of robots for automated orchard operations but also advance digital twin technology, enabling the facilitation of field robotics across various domains.

## Code

The implementation has been integrated into [PSS](https://github.com/perrydoremi/PlantSegStudio).

## Data

Please download the data used in this study [here](https://cornell.box.com/s/9ejbks86k7njv7274qbves29p410s3q4).

## License
MIT License

## Citation
If you find our work useful in your research, please consider citing: 

```bibtex
@article{qiu2025joint,
  title={Joint 3D Point Cloud Segmentation using Real-Sim Loop: From Panels to Trees and Branches},
  author={Qiu, Tian and Du, Ruiming and Cheng, Lailiang and Jiang, Yu},
  journal={arXiv preprint arXiv:2503.05630},
  year={2025}
}

@misc{du2025scalableorganlevel3d,
    title={Towards Scalable Organ-Level 3D Plant Segmentation: 
           Bridging the Data-Algorithm-Computing Gap}, 
    author={Ruiming Du and Guangxun Zhai and Tian Qiu and Yu Jiang},
    year={2025},
    eprint={2509.06329},
    archivePrefix={arXiv},
    primaryClass={cs.CV},
    url={https://arxiv.org/abs/2509.06329}
}
```
