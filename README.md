# ASIC-2024

> 🚧 This document will be updated continuously prior to the live tutorial on April 30th, 2024.  


This repo serves as the primary record and Q+A forum for the pre-conference training titled "Python Packages" during the "Hands-on with data (coding workshop)" section. The tutorial is led by Dr. David H. Hagan and Jared Briskman of QuantAQ, Inc.


The goal of this session is to leave with an understanding of the tools available to make publication-quality air sensor figures using Python and how to use them.



## The official description:

> Preparing visually appealing and scientifically valid figures is crucial for ensuring positive outcomes for communities and scientists alike when using air sensors. In attending this tutorial, you will learn how to make puplication-quality figures to communicate the air sensor data you've collected for use in presentations, reports, and more. This session focuses on using the open-source programming language, python, to visualize data effectively. We will cover how to prepare your data and munge it into the correct format, create common figures, and use the `atmospy` python library to make your data visualization life easier.


### Session Outline

Below is the session outline. More details to come:

| Time | Type | Description |
|:----:|:----:|:------------|
| 20-30 min | presentation | An introduction to plotting in Python|
| 10 min | code | Install `atmospy` and dependencies (we will be there to help if needed!)|
| 30 min | presentation + code | Overview of foundational air quality figures with `atmospy` |
| 20-30 min| code | Making plots with your own data (or provided example datasets) - we will be there to walk around and help you with your own datasets and/or answer questions |


## Pre-Conference Work

### Installation of atmospy

We ask that prior to attending the conference training session, you install `atmospy` and its dependencies into your preferred python development setup following the instructions in the [official documentation](https://dhhagan.github.io/atmospy/index.html). It's unclear what the conference WiFi situation will be, so doing so ahead of time may reduce issues.


If you have any issues with installation, please open an issue on [this repository](https://github.com/quant-aq/ASIC-2024/issues). **Note: you will need to create a GitHub account to do so if you don't already have one**. If you can't create an issue for some reason, please email david.hagan@quant-aq.com.

### Help, I don't have python installed at all!

If you don't have any existing local python environment (and the conference wifi is amenable), you can use Google Colab as an easy browser-based python notebook tool for the tutorial instead. You will need a Google account, then head to [https://colab.new/](https://colab.new/) and run:
```
%pip install atmospy
import atmospy
```
you should be able to follow along with the tutorial. 

### Bring your own data (if you'd like to)

There will be opportunities during the training to try making figures using your own data. Please feel free to come prepared with your own data in csv (or similar tabular) format. Your data should be air quality or air sensor data and should be a time-series. Otherwise, there are no additional requirements!


## Resources

| Title | Link | 
|:------|:----:|
| Slides |  Available [here](/ASIC%202024%20Tutorial%20[Hagan].pdf) |
| Atmospy GitHub Repo | Available [here](https://github.com/dhhagan/atmospy?tab=readme-ov-file) |
| Atmospy Docs | Available [here](https://dhhagan.github.io/atmospy/index.html) |  


