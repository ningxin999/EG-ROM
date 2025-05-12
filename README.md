# Sequential Calibration of Soil Parameters Using a Two-Step Surrogate for High-Dimensional Geotechnical Outputs

This repository contains the MATLAB based implementation of the PCA-PCE reduced order modelling for geotechnical correlated high-dimensional outputs and uncertainty quantification. 
![alt text](image.png)
Please cite this work, in case you use and/or refer to the PCA-PCE UQ and sequential Bayesian calibration worke.

@article{yang2024two,
  title={A two-step surrogate method for sequential uncertainty quantification in high-dimensional inverse problems},
  author={Yang, Ningxin and Le, Truong and Potts, David M and others},
  journal={arXiv preprint arXiv:2407.11600},
  year={2024}
}

---

The present software and the related examples rely partially on the UQlab library.
- https://www.uqlab.com/ 

---
Cases A, B, C and D refers to the usage of DR and the number of training numbers.
Here, we can control the code switch:AnParam.DR and AnParam.TrainDataPerc to reproduce the results.
e.g., AnParam.TrainDataPerc = 1 (FE training run number = 138)