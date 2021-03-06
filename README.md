# DummyForMRI

<p align="center"> 
<img src="https://github.com/SebastianoF/DummyForMRI/blob/master/screenshots/Danny_3d_view.jpg" width="550">
</p>

Very simple dummy generator for non-realistic multi-atlas. 
Can be useful for quick testing of pipelines and algorithms.
 
### Features

+ Pure python 3.6, backcompatible with python 2.7 and 3.5.
+ Simple creation of headlike shape phantom and ITK-snap compatible labels descriptor.
+ Open source, open to improvements and available on [github](https://github.com/SebastianoF/DummyForMRI).
+ About the geometry: the random variability between randomly generated shape makes an affine registration not enough to compensate for the geometrical differences.

### Install

Suggested installation in [development mode](https://avolkov.github.io/installing-python-packages-in-development-mode.html):
```bash
cd <folder where to clone the repository>
git clone https://github.com/SebastianoF/DummyForMRI.git
cd DummyForMRI
pip install -e .
```

### Before you start...

A list of other options:

+ [BrainWeb](http://brainweb.bic.mni.mcgill.ca/brainweb/): a realistic and accurate synthetic generated multi-atlas, one modality and its ground truth segmentation for 
20 subjects (see as well the helper [BrainWebRawToNifti](https://github.com/SebastianoF/BrainWebRawToNifti)).     
+ [ICW-fMRI-GAN](https://github.com/BlissChapman/ICW-fMRI-GAN): code for a conditional wasserstein generative adversarial network (ICW-GAN) that is trained to generate synthetic 
fMRI data samples
+ [Phantomas](https://github.com/ecaruyer/phantomas): Python 2.7 and Cython based library for the creation of realistic tissue 
phantoms in diffusion MRI. It is intended as a tool for the validation of methods in acquisition, signal and image 
processing, local reconstruction and fiber tracking.

### Usage

[Examples](https://github.com/SebastianoF/DummyForMRI/tree/master/examples) folder is the starting point.

### Licencing and Copyright

Copyright (c) 2018, Sebastiano Ferraris. DummyForMRI is provided as it is and 
it is available as free open-source software under 
[MIT License](https://github.com/SebastianoF/DummyForMRI/blob/master/LICENCE.txt)


### Acknowledgements

+ This repository is developed within the [GIFT-surg research project](http://www.gift-surg.ac.uk).
+ Sebastiano Ferraris is supported by the EPSRC-funded UCL Centre for Doctoral Training in Medical Imaging 
(EP/L016478/1) and Doctoral Training Grant (EP/M506448/1). 




