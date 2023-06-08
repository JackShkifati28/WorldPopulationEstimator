# WorldPopulationEstimator

## Description
This program utilizes a text file with data ranges of the world populations corresponding to their respective years. To process this data, we first declare two arrays, one for the years and another for the world population. Arrays are useful here as they can store a fixed-size collection of elements of the same data type, allowing us to segregate years and world population data.

We then create a method to scan the data from the file, populate both arrays and count the number of rows. However, as the data is unorganized, we need to sort the arrays using the bubble sort method. Bubble sort is a simple sorting algorithm that repeatedly compares and swaps adjacent elements until no more swaps are needed.

Once we finish sorting, we create a method to print all millennium years, i.e., years with no remainder when divided by 1000.

To further analyze the data, we want to get the statistics (mean, median, and standard deviation) of the world population for the years ranging from -5000 to -1000, 1000 to 1900, and 2000 to 2020. Therefore, we create three different arrays to store the world population for these three different time periods. Then we create methods to calculate the mean, median, and standard deviation for each time period.

- **Mean**: Also known as the arithmetic mean or average, it sums up all the values and divides by the number of values. It gives us the estimated world population for different time periods.

- **Standard deviation**: This number indicates how measurements for a group spread out from the average (mean), or expected value.

- **Median**: This is the value separating the higher half from the lower half, essentially the "middle" value.

Finally, we implement a method for the least squares regression, a line that minimizes the vertical distance from the data points to the regression line. This can help us approximate the world population as a function of the year, assuming the growth of the population is linear.

