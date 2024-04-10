# High definition psychrometric chart
A high definition psychrometric chart for teaching humidification operations without the pain. The chart was freely adapted from a working document of a French company defunct in 1970, so I guess the data are in the public domain now. The original that I still own in something close to A1 format is a real piece of art drawn by hand. It deserved a digitalization, here it is.

I used it as student in chemical engineering around 1999 and use it for teaching the same since 2007. This is by far the most comprenhensive version I've ever found, it contains some uncommon features:
- The iso-enthalpy lines and the wet bulb temperature are drawn separately, which is very uncommon as both are generally confused;
- A compass to generate the unit operation of air saturation with the minimal quantity of a given water source is given, as it is rather difficult to plot usually (despite being very important to teach as very first example);
- It ranges between -15°C and 50°C, which allows studying problems from snow-blowers to cooling towers for nuclear energy with a single chart;
- The enthalpy units are in kilocalories per kg on purpose. It allows simplifying a calculation step for cooling towers, because the specific heat capacity of water is ny definition 1 kcal/kg.

 I've modified some parts of the original chart:
 - The compass for air saturation with minimal quantity of water is more compact and easier to use as it was initially spread on the whole chart and barely readable as sunk among other informations;
 - It features the slope for finding interface enthalpies for cooling towers operations (which is not exactly vertical);
 - The vapor pressure of water is given in Pa instead of kg per square centimeters;
 - x-axis and y-axis are othogonal now.

The repo contains a high resolution pdf and the law res raster source files I used to digitalize it (it's a scan of an A3 reduction the original chart but I do not remind where I got it). The PNG file is just a low res preview, do not use it. The chart is meant to be printed in A3 for better reading even if A4 may be OK for students. 

Why not using a code for doing this ? Because pen and paper are enough !

![](/Psychrometric_chart.png)
