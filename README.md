# Quantifying-Land-Cover-Change-Using-R-code

The code is used to calculate the land cover transition matrix and the number of pixels gained and lost for each land cover class. 
The code then loads the two land cover maps, which are in .tif format. In the example, the first land cover map is for the year 2006 and the second land cover map is for the year 2018.
The code then creates a land cover transition matrix. The land cover transition matrix is a square matrix that shows the number of pixels that changed from one land cover class to another between the two time periods. The code uses the crosstab() function to create the land cover transition matrix. The crosstab() function takes two rasters as input and returns a table that shows the counts of cells in each combination of values. The code then saves the land cover transition matrix as a CSV file. 
Further, the code then calculates the number of pixels gained and lost for each land cover class. The number of pixels gained is the number of pixels that changed from one land cover class to another, while the number of pixels lost is the number of pixels that remained in the same land cover class.
The code uses the rowSums() function to calculate the sum of each row in the land cover transition matrix. The diag() function returns the diagonal elements of a matrix. The difference between the row sums and the diagonal elements is the number of pixels gained or lost for each land cover class.
The code then calculates the percentages of gains and losses. The percentage of gains is the number of pixels gained divided by the total number of pixels, while the percentage of losses is the number of pixels lost divided by the total number of pixels.
The code uses the / operator to divide the number of pixels gained or lost by the total number of pixels. The results are then multiplied by 100 to express the percentages as percentages.
The code prints the results of the calculations to the console.
The code can be used to analyze land cover change over time. It can be used to identify the land cover classes that are gaining or losing pixels, and to calculate the percentages of gains and losses. This information can be used to better understand the factors that are driving land cover change and to develop strategies to mitigate or adapt to these changes.




