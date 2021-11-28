# APSIM-VarDecomp

### Background
Developed by Jonathan Ojeda (7/11/2021) (some pieces of the code were initially developed by Dr Bahareh Kamali, University of Bonn)

This code is able to retrieve APSIM Next Generation outputs and carried out a variance decomposition analysis to identify the main contributors to the variance in selected model outputs.

_**Functionality:**_ Calculate the main (ME) and total effect (TE) of a series of factors on the variability of a selected variable (in this example crop biomass).

ME explains the share of the components to model output variability without interactions, 
i.e. if ME=1, the assessed factors explain the entire proportion of model output variability, 
but if M<1, residuals exist which means additional factors are required to explain this variability. 
TE represents the interaction of a given factor with other factors, i.e. high TE values for a given 
factor denote high interactions of that factor with other factors, therefore, TE does not include residuals.

### Main theoretical reference
* [Monod et al., 2006](http://ndl.ethernet.edu.et/bitstream/123456789/43022/1/53.pdf#page=70)

### Examples
* [Ojeda et al., 2021](https://www.sciencedirect.com/science/article/pii/S0378429021001593?casa_token=LqK9vdXDrgUAAAAA:oq_bfMo0l6VA9Rxu0gmf3tH5x2SZOJK4dP7GH6jVn30KFn_AYfDhbKBDhL7EkPQcJAmiDC-S3t1c)
* [Webber et al., 2018](https://www.nature.com/articles/s41467-018-06525-2)

### How to cite the use of this code?
_Ojeda, Jonathan J., Ehsan Eyshi Rezaei, Bahareh Kamali, John McPhee, Holger Meinke, Stefan Siebert, Mathew A. Webb, Iffat Ara, Frank Mulcahy, and Frank Ewert. "Impact of crop management and environment on the spatio-temporal variance of potato yield at regional scale." Field Crops Research 270 (2021): 108213._