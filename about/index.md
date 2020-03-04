---
layout: page
title: About the Interface
tags:
  - about
  - Jekyll
  - theme
  - moon
date: {}
comments: false
published: true
---
    
<center><a href="https://github.com/abhiii29/Segmentation"><b>The script</b></a> is a minimal, one click model training interface.</center>

## Installation
* Import the python script to the ImageJ/Fiji installation directory
* Create a directory structure for Original data, Validation data and Test data
	* Every directory should have an Original image directory and a labelled image directory

## Python Dependencies
### Conda
* Tensorflow v1.15 (recommended: v1.12 for default compatibility with ImageJ)
* Keras v2.2.4
* Matplotlib
* Pillow
* Scikit-image
* Jupyter

### Pip
* CSBDeep
* Tables

## Features
* Deep Learning using neural networks
* Weka Segmentation
* One click model creation
* Error calculation
* Best Weka model selection based on error
