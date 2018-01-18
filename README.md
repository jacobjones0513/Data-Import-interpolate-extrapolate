# Data-Import-interpolate-extrapolate

The ﬁle ”co2 mm mlo.txt” contains data on the CO2 content in the atmosphere as measured at the Mauna Loa Observatory. It has a signiﬁcantly long header describing the data and then delimited values after. You will have to inspect the ﬁle to see the line number for which the header ends and data begins using an editor or other tool.

1a: Write a script to read the data into a single numpy array and use the array indexing of python to plot the decimal date vs. average for the ﬁrst 60 months. Comment on the shape of the data and any anomalies you see. 

1b: Investigate the use of the pyplot saveﬁg command to save a hardcopy of the plot in 1a, and create a plot ﬁle in jpg format. Learn about and use the plt.ylim function to restrict the plotted range of the y-axis to enhance the view of the data oscillations. Include the plot ﬁle in your submission 

1c: Use a for loop or direct vectorized equations to plot the diﬀerence between the interpolated data and the seasonally corrected trend. Save a hardcopy and include in your submission. 

1d: With the instructor explore and use the numpy savetxt function to write a ﬁle containing only the decimal date and trend columns. Write all values to keep only 3 decimal places using the ”fmt” parameter. 
