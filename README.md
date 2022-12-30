#   Stokes Inversion for GST/NIRIS Using Stacked Deep Neural Networks
[![DOI](https://github.com/ccsc-tools/zenodo_icons/blob/main/icons//sddn.svg)](https://doi.org/10.5281/zenodo.7494967)

## Authors
Haodi Jiang, Qin Li, Yan Xu, Wynne Hsu, Kwangsu Ahn, Wenda Cao, Jason T. L. Wang, Haimin Wang 


## Contributor
Yasser Abduallah

## Abstract

Obtaining high-quality magnetic and velocity fields through Stokes inversion is crucial in solar physics. In this paper, we present a new deep learning method, named Stacked Deep Neural Networks (SDNN), for inferring line-of-sight (LOS) velocities and Doppler widths from Stokes profiles collected by the Near InfraRed Imaging Spectropolarimeter (NIRIS) on the 1.6 m Goode Solar Telescope (GST) at the Big Bear Solar Observatory (BBSO). The training data for SDNN are prepared by a Milne-Eddington (ME) inversion code used by BBSO. We quantitatively assess SDNN, comparing its inversion results with those obtained by the ME inversion code and related machine-learning (ML) algorithms such as multiple support vector regression, multilayer perceptrons, and a pixel-level convolutional neural network. Major findings from our experimental study are summarized as follows. First, the SDNN-inferred LOS velocities are highly correlated to the ME-calculated ones with the Pearson product-moment correlation coefficient being close to 0.9 on average. Second, SDNN is faster, while producing smoother and cleaner LOS velocity and Doppler width maps, than the ME inversion code. Third, the maps produced by SDNN are closer to ME's maps than those from the related ML algorithms, demonstrating that the learning capability of SDNN is better than those of the ML algorithms. Finally, a comparison between the inversion results of ME and SDNN based on GST/NIRIS and those from the Helioseismic and Magnetic Imager on board the Solar Dynamics Observatory in flare-prolific active region NOAA 12673 is presented. We also discuss extensions of SDNN for inferring vector magnetic fields with empirical evaluation.

## Binder

This notebook is Binder enabled and can be run on [mybinder.org](https://mybinder.org/) by using the link below.


### run_SDNN.ipynb (Jupyter Notebook for SDNN)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ccsc-tools/SDNN/HEAD?labpath=run_SDNN.ipynb) 

Please note that starting Binder might take some time to create and start the image.

For the latest updates of SDNN refer to [https://github.com/deepsuncode/SDNNStokesInversion](https://github.com/deepsuncode/SDNNStokesInversion)



## References
Inferring Line-of-sight Velocities and Doppler Widths from Stokes Profiles of GST/NIRIS Using Stacked Deep Neural Networks. Haodi Jiang, Qin Li, Yan Xu, Wynne Hsu, Kwangsu Ahn, Wenda Cao, Jason T. L. Wang, Haimin Wang, The Astrophysical Journal, Volume 939, Issue 2, id.66, 12 pp., November 2022.

https://iopscience.iop.org/article/10.3847/1538-4357/ac927e

https://arxiv.org/abs/2210.04122 