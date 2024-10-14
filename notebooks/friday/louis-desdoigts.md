---
title: "Louis Desdoigts"
---

# Louis Desdoigts
## Amigo: Differentiable modelling of JWST AMI mode

The Aperture Masking Interferometer (AMI) on board the James Webb Space Telescope (JWST) has a unique place in observational astronomy as the first imaging interferometer in space, promising highly-precise observations resistant to optical aberrations. While the optical system and Point-Spread Function (PSF) are very stable, the infrared detectors on board suffer from a series of non-linearities – primarily charge migration or the “brighter-fatter effect” that, while challenging for other observing modes, are ruinous to the visibility calibration of the AMI mode. Local nonlinear effects produced cannot be straightforwardly corrected in the Fourier domain. Efforts using the existing pipelines have delivered some improvements, but outcomes remain far from the theoretical photon-noise limit of the instrument. This manuscript presents initial work using a fundamentally different approach: the joint implementation of a differentiable physics model of the optics, and a machine-learned Effective Detector Model (EDM), using dLux. These are trained together end-to-end, by gradient descent using the full ensemble of point-source reference targets so far observed by AMI. We infer highly- precise metrology of the AMI and NIRISS optical systems, a preliminary EDM which restores commissioning data to near-ideal precision, and illustrate initial and final residual noise floors representing the present state of this ongoing project.
