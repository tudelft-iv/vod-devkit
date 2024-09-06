# VoD-P devkit
Welcome to the downloadable driverless vehicle software page for the View-of-Delft Prediction (VoD-P) dataset. Click on the green box above labeled "Code" to download a copy of the software described below.

![](https://www.vod.org/public/images/road.jpg)

## Overview
- [Changelog](#changelog)
- [Devkit setup](#devkit-setup)
- [VoD-P](#vod)
  - [VoD-P setup](#vod-setup)
  - [Panoptic VoD](#panoptic-vod)
  - [VoD-P lidarseg](#vod-lidarseg)
  - [Prediction challenge](#prediction-challenge)
  - [CAN bus expansion](#can-bus-expansion)
  - [Map expansion](#map-expansion)
  - [Map versions](#map-versions)
  - [Getting started with VOD](#getting-started-with-vod)
- [Known issues](#known-issues)
- [Citation](#citation)

## Changelog


## Devkit setup
The devkit is tested for Python >=3.6.
To install Python, please check [here](https://github.com/nutonomy/vod-devkit/blob/master/docs/installation.md#install-python).

TODO: Our devkit is available and can be installed via [pip](https://pip.pypa.io/en/stable/installing/) :
```
pip install vod-devkit
```
For an advanced installation, see [installation](https://github.com/nutonomy/vod-devkit/blob/master/docs/installation.md) for detailed instructions.


## VoD-P

### VoD-P setup
To download VoD-P you need to go to the [Download page](), 
create an account and agree to the VoD [Terms of Use]().
After logging in you will see multiple archives. 
For the devkit to work you will need to download *all* archives.
Please unpack the archives to the `/data/sets/vod` folder \*without\* overwriting folders that occur in multiple archives.
Eventually, you should have the following folder structure:
```
/data/sets/vod
    samples	-	Sensor data for keyframes.
    sweeps	-	Sensor data for intermediate frames.
    maps	-	Folder for all map files: rasterized .png images and vectorized .json files.
    v1.0-*	-	JSON tables that include all the meta data and annotations. Each split (trainval, test, mini) is provided in a separate folder.
```
If you want to use another folder, specify the `dataroot` parameter of the VOD class (see tutorial).


### Map expansion


### Map versions
Here we give a brief overview of the different map versions:
- **VoD-P v1.0**: 

### Getting started with VoD-P


## Known issues

## Citation
Please use the following citation when referencing [VoD-P]():
```
@article{
}
```

