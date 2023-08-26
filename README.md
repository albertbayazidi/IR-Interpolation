# IR_interpolator

This project focuses on the initial testing and exploration of data interpolation from the AMG8833 sensor. The goal is to eventually develop a comprehensive IR camera using the insights gained from this stage.

## Overview

The main objective of this project is to understand the feasibility of data interpolation techniques applied to the output of the AMG8833 sensor. The AMG8833 sensor provides thermal data for a 8x8 pixel grid, through interpolation, we seek to enhance this resolution.

## Contents

In this repository, you will find:

* **Dataset**: The data collected from my AMG8833 sensor 
- **Interpolation Script**: The code used to perform data interpolation on the output from the AMG8833 sensor.
- **Future Plans**: Discussion of how the gathered insights will be utilized in the subsequent stages of developing a proper IR camera.


## Demo

https://github.com/albertbayazidi/IR-Interpolation/assets/102351774/d3559252-e7f2-40f6-a795-8a5bb3ff11f0


## Future Steps

* Implement similar code in C++
- Test interpolation on ESP32
- Create a prototype with a built-in screen


If the ESP32 is unable to satisfy a decent framerate, I will do the interpolation on a server and just render the result on an ESP32. This, however, is a last resort. Before this, I will try splitting the work on both cores and maybe even iterative methods
