

<p align="center">
  <img src="pyiwr.png" alt="pyiwr" width="50%">
</p>






# pyiwr

pyiwr is an advanced open-source library developed by researchers at the SIGMA Research Lab at IIT Indore. This powerful tool is designed to effortlessly convert raw ISRO Doppler Weather Radar (DWR) data files and correct MOSDAC radar NetCDF files into Py-ART compatible NetCDF files. pyiwr also provides a range of useful tools and visualization functions to facilitate working with and analyzing weather radar data.

## Features

- Converts raw ISRO Doppler Weather Radar (DWR) data files into Py-ART compatible NetCDF files.
- Provides convenient tools for data processing and analysis.
- Offers visualization functions for better understanding and interpretation of radar data.

## Installation

pyiwr can be installed in different ways depending on your preference. Below are two recommended methods:
```shell
conda create -n srt python=3.9 jupyter arm_pyart pandas git -c conda-forge
conda activate srt
pip install git+https://github.com/nitigsingh/pyiwr.git


