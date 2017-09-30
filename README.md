**User Profile:**

The customer is assumed to be young. He has enough buying power to buy expensive cars and he is interested in cars with great speeds.

**Horse Power Vs Weight:** 
barplot(foo$hp,ylab = "Horse Power", xlab="Weight",col=rainbow(15), names.arg=foo$wt,main="Horse Power vs Weight",las=2)
The customer will look for a car that has high horse power for more speed. The car should also be light for attaining fast speeds quickly.
**Transmission Vs Gear:**
barplot(foo$am,ylab = "Transmission", xlab="Number of Gears",col=rainbow(15), names.arg=foo$gear,main="Transmission vs Gear",las=2)
The customer can be interested in either an automatic or a manual car and he would also want to know the number of gears the vehicle has. 
**Speed Vs Engine CC:**
barplot(foo$qsec,ylab = "Time To Travel 1/4 Mile", xlab="CC",col=rainbow(15), names.arg=foo$disp*10,main="Speed vs Engine CC",las=2)
The customer will look for a car that has a high speed as well as a high engine CC. These factors are very important.
**Miles Per Gallon Vs Number of Cylinders:**
barplot(foo$mpg,ylab = "Miles per Gallon", xlab="Number of Cylinders",col=rainbow(15), names.arg=foo$cyl,main="Miles per Gallon vs Number of Cylinders",las=2)
The customer will be shown how many cylinders the car has and how many miles it travels per gallon of fuel i.e. the mileage. A higher number of cylinders means more driving force the car has.
