# Digilent_AD_PyTools
## Python Tools for the Digilent Analog Discovery

This is a project I am working on to create a python toolset for the [Digilent Analog Discovery]( http://store.digilentinc.com/analog-discovery-2-100msps-usb-oscilloscope-logic-analyzer-and-variable-power-supply/) that is a remarkable tool for analog and digital EE’s or want to be’s. While there is an SDK for the python for the Analog Discovery it is not nice and not something I want to deal with.

 Instead, I am focusing on just making an Ipython Widget based GUI to collect all the data and settings from my use of the Analog Discovery. I am especially anal about this since I have had to comply with NADCAP and the [DICONDE](https://www.astm.org/SNEWS/OCTOBER_2003/voelker_oct03.html) / [DICOM]( https://en.wikipedia.org/wiki/DICOM) standards in industrial and medical imaging. Where since imaging is just spatially distributed electrical signals (aka oscilloscope readings) it annoys me to no end that there is not an IEEE standard for digital scopes that is an ASTM DICONDE equivalent. So that we know when, where, settings, what was measured on what input, and what outputs (if applicable) where used and their settings. I hope that in future versions of Waveforms this become standard output but as of 5/2/17 that is not the case to my knowledge.

Right now this is very much in the proto-prototype stage, but the code is open for use for the time being if anyone wants it. 
When the data porting is done will work on saving, followed by adding processing abilities 
Analog Discovery and Waveforms are products of Digilent Inc. (an NI company) 

