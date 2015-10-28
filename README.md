# SRE

This contains the work done as part Supervised Research Project, under Prof. Shankar Balachandran. 

Right now I am trying to build a float into int8 multiplier, which should be considerable faster than default float multiplier. I has major applications in image processing convolution kernels.

# Multiplier Design:

A basic 24x8 bit multiplier based on Wallace tree multiplication. 
The 32bit kernel values are all less than one and 8bit int represents a pixel, so that much error can be tolerated the circuit is designed on that basis.
