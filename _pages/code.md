---
layout: archive
title: "Code"
permalink: /code
author_profile: true
---

## [Python statistical shape and appearance modelling (pyssam)](https://github.com/jvwilliams23/pyssam)

We have developed an API for creating statistical shape and appearance models (SSAMs) from landmark data. This can be used to extract features that describe correlations in complex shapes such as human organs. These SSAMs can also serve as a prior constraint for new segmentation algorithms.

## [Neural network modelling for turbulent dispersion](https://github.com/jvwilliams23/turbulent-dispersion-neuralSDE)

The code to train a stochastic model for turbulent dispersion is available on github. We also provide OpenFOAM code to read the neural network parameters and use the model in a simulation. The OpenFOAM code could be adapted to other stochastic models (theoretical or data-driven), and for other physical phenomena. The training script could be adapted to new training data.

## [CNN Toolkit for segmentation of airways and lungs from CT](https://github.com/jvwilliams23/respiratoryCNN-toolkit)
We provide code for training and segmenting airways and lungs from CT scans using CNNs (U-Net and ENet). Lung segmentation is performed by [lungmask](https://github.com/JoHof/lungmask) which was trained on better data than was available to us. The lung segmentation can be used to crop the chest CT image to the lung lobes bounding box which improves efficiency of the airway segmentation.

## [deepLungFoam solver](https://github.com/jvwilliams23/deepLungFoam)

We couple an OpenFOAM simulation to a 0D resistance-compliance model that approximates outlet pressure. This can be used to simulate flow distribution for outlets in biological flows such as lung airways or vascular system.

## [OpenFOAM Stokes boundary condition for particles](https://github.com/jvwilliams23/StokesWallMPPIC)

We have implemented a BC for particle deposition on walls based on particle Stokes number. High inertia particles will rebound and low inertia particles will stick to the wall. We have used this for deposition in the mucus layer of the airways.

