# Multichannel-rVAE

Disentangle spatial correlations from hyperspectral data sets using the basis of rotationally invariant variational autoencoders (rVAEs). 
The *multichannel* rVAE is introduced here, where multiple channels are used with the rVAE neural network to learn spatial features contained in the data.
Channels are broadly defined, but are typically that of energy or wavelength, for example, RGB is a 3-channel image or an EELS image is something like a 2048-channel image (# of energy pixels).
This is demonstrated on STEM-EELS images in the following notebook:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kevinroccapriore/Multichannel-rVAE/blob/main/Multilchannel_rVAE_EELS.ipynb)

In principle, these channels could even be snapshots in time from the same physical channel, however this has not been explored.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10449468.svg)](https://doi.org/10.5281/zenodo.10449468)
