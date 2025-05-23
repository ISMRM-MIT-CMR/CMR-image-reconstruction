# Laying the foundations of cardiovascular MR 
# Reconstruction: Faster & Better Scans II - Hands-on Tutorial

## Introduction
*by [Thomas Kuestner](www.linkedin.com/in/thomaskuestner)* and *[Kerstin Hammernik](https://www.linkedin.com/in/khammernik/)*

In this hands-on, you will get introduced to the world of MRI reconstruction, ranging from conventional reconstruction techniques to machine learning solutions. We start with examining the raw k-space data and coil-sensitivity maps and build the multi-coil forward and adjoint operator. In accelerated imaging, the k-space is undersampled leading to an ill-posed problem. To solve this linear inverse problem, the reconstruction is often regularized. First, we solve the linear and a regularized reconstruction problem conventionally, which allows us to deeply understand where we can later connect to machine learning. These regularizations can also later be learned by neural networks. Machine learning reconstructions thereby differ in their input and targeted application: Image enhancement, direct mapping, physics-based unrolling and distribution-based methods. We will shortly touch upon image enhancement and physics-based unrolling and highlight key factors for real-valued and complex-valued development here.

The work uses the [MERLIN](https://github.com/midas-tum/merlin) package and integrates hands-on examples from the MERLIN repository.

## Getting started
You may either run the Jupyter notebook locally on your laptop (computational demand is low) or via 

### Google Colab
Solution: <a target="_blank" href="https://colab.research.google.com/github/ISMRM-MIT-CMR/CMR-image-reconstruction/blob/master/HandsOn_MRI_reconstruction.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a><br/>
Exercise: <a target="_blank" href="https://colab.research.google.com/github/ISMRM-MIT-CMR/CMR-image-reconstruction/blob/master/HandsOn_MRI_reconstruction_exercise.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
<br/>
### Binder
Solution: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ISMRM-MIT-CMR/CMR-image-reconstruction/master?urlpath=%2Fdoc%2Ftree%2FHandsOn_MRI_reconstruction.ipynb) <br/>
Exercise: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ISMRM-MIT-CMR/CMR-image-reconstruction/master?urlpath=%2Fdoc%2Ftree%2FHandsOn_MRI_reconstruction_exercise.ipynb) 
