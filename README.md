# SOM
The requirement is shown in Assignment2.pdf Question4.

## Getting Started
Implement the kohonen self organizing map(SOM).  

## Analysis
For the same sigma, as increasing the epochs, the border is much clear. And the same color area which cluster together is larger, which can show clearly on sigma10, the second row.  
For the same epoch, as increasing the sigma, the image and the borders among different colors are more blur. And the color image is larger, such as epoch40 & sigma70 pink area is larger than epoch40 & sigma1 pink area.  

For changing sigma_0:  
If want to change sigma_0, then just change the code cell[4], where there is a sentence:  
sigmas = [1, 10, 30, 50, 70] --> sigmas = [whatever number you want to test]. 
Changing sigmas_list into another_sigmas_list can replicate the output successfully.


