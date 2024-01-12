Cosine weighted averaging is a crucial technique employed in the analysis of Ocean/ Met data to address the impact of Earth's curvature. 


Averaging of gridded data in python simply add up all the values in each grid and divided by the total number of grids assuming area for each grids are same. But this make a error in Ocean/Met data that are spanned in global grid due to earth’s curvature. The area for equatotail grids are generally larger than the higher latitude. A  weighted average technique for each grid based on its latitude is required. This method involves multiplying each data point by the cosine of the latitude at which it was recorded.
