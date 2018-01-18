# Data-Import-interpolate-extrapolate

#1a
import numpy as np
import matplotlib.pyplot as plt 

info = np.loadtxt(fname='co2_mm_mlo.txt')

#print(info[0])
#I am calling the first 60 values listed in columns 1 and 2 in order to plot them 
#against each other.
decDate=np.copy(info[:60,2])
avgCO2=np.copy(info[:60,3])

plt.scatter(decDate,avgCO2)
plt.ylim(310,330)
plt.xlabel('Date')
plt.ylabel('Avg CO2')
plt.title('CO2 Level')
plt.show()

#The data points appear as a wave that tends to increase over time.
#see
