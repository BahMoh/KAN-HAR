# Human Activity Recognition using Kolmogorov–Arnold Network (KAN-HAR)

This repository provides an open-source implementation of **Human Activity Recognition (HAR)** using a **single three-axis accelerometer** and the **Kolmogorov–Arnold Network (KAN)**. The framework leverages the KAN's ability to model complex nonlinear relationships efficiently, providing competitive performance while maintaining interpretability and a reduced parameter count.

## Features

- Efficient HAR using a **single three-axis accelerometer**
- Hand-crafted features extracted from accelerometer channels
- Utilizes **KAN** for feature learning and classification
- Works with **MotionSense dataset** (smartphone-based motion sensor signals)
- Preprocessing and normalization of accelerometer and gyroscope data
- Superior classification performance compared to conventional deep neural networks
- Reduced model parameter count for efficient real-world deployment

## Dataset

The experiments use the **MotionSense dataset**, which contains smartphone-based motion sensor signals for various physical activities, such as walking, jogging, upstairs, downstairs, sitting, and standing.

The dataset can be downloaded from:  
[Accelerometer Data](https://github.com/mmalekzadeh/motion-sense/blob/master/data/B_Accelerometer_data.zip?raw=true)


## Citation
If you find this work useful, please cite the following article:

```bibtex
@article{alikhani2025contrastive,
  title={Contrastive-KAN: A Semi-Supervised Intrusion Detection Framework for Cybersecurity with scarce Labeled Data},
  author={Alikhani, Mohammad and Kazemi, Reza},
  journal={arXiv preprint arXiv:2507.10808},
  year={2025}
}
```
