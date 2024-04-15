# AnalogSNN_on_Hardware

Python scripts for the data acquisition of the spiking neuron implemented on hardware.

**keysight_msox6004a_VI** contains the instructions for the reading and configuration for the oscilloscope, the pre-requisites for the program are PyVisa, Numpy, Matplotlib, and the VISA drivers (this one has to be installed from the NI-VISA installer)

**AFG3251C** contains the instructions for the writing and configuration of the Tektronix AFG3251C function generator, the program occupies the same NI-VISA driver to communicate

**VI_testbench** contains the program that controls the oscilloscope and function generator for tuning curve of the SNN 
