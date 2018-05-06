## Table of Content
1. [Problem statement and motivation](#Problem-statement-and-motivation)
2. [High-level summary of the procedure](#High-level-summary-of-the-procedure)
3. [HDR radiance image reconstruction (Debevec's algorithm)](#HDR-radiance-image-reconstruction-(Debevec's-algorithm))
4. [Tone Mapping algorithms](#Tone-Mapping-algorithms)
   1. [Reinhard's algorithm](#Reinhard's-algorithm)
   2. [Durand's algorithm](#Durand's-algorithm)
5. [Results](#Results)
6. [Conclusion and future work](#Conclusion-and-future-work)
7. [Reference](#Reference)


### Problem statement and motivation
The range of intensity of light in real world is approximately **10** orders of magnitudes (e.g., star-lit scene vs. sun-lit snow) and it can be over **4** orders of magnitudes in one scene (e.g., shadows vs. highlights). However, the range of intensity of light that can be captured by normal cameras and can be displayed by normal monitors is only about **2** orders of magnitudes. The ability of capturing and displaying both very dark and very bright at the same time is characterized by the **dynamic range** of the device. The dynamic range is defined by the following equation:

<p align="center">
  <img src="equations/dynamic_range.gif" />
</p>

Where ![](equations/bmax.gif) is the maximum possbile photon energy (full potential well) and ![](equations/bmin.gif) is the minimum detectable photon energy (in the presence of noise). The larger the dynamic range is, the higher the ability of distinguishing different brightness. The following table shows the dynamic ranges of several devices.

Device          |  ![](equations/bmax.gif):![](equations/bmin.gif) | Dynamic Range
:--------------:|:------------------------------------------------:|:-------------:
Human Eye       | 1,000,000:1                                      |120
HDR Display     | 200,000:1                                        |106
Digital Camera  | 4096:1                                           |72.2
Film Camera     | 2948:1                                           |66.2
Digital Video   | 45:1                                             |33.1




### High-level summary of the procedure
### HDR radiance image reconstruction (Debevec's algorithm)
### Tone Mapping algorithms
#### Reinhard's algorithm
#### Durand's algorithm
### Results
### Conclusion and future work
### Reference




