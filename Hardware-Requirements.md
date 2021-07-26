# Hardware Requirements for C-Kit 

## WiFi
As the C-Kit must be able to handle WiFi, it has to have a WiFi facility.

## WiFi antennas

### WiFi nearfield antenna
For the nearfield-communication it has to have a near-field antenna. So it can provide WiFi in the range of 100 m radius under good conditions.

### WiFi long-distance antenna
To make long distance data-transmission possible and more reliable, there must be an antenna to bundle WiFi so it can reach far more than 100m. The longer the better.

## Power supply

### Power bank
As the C-Kit must operate in areas where there is no electricity at all, it must be selfpowered. As a buffer, there will be a regular powerbank one can buy in any store. 
The more capacity it has the better. If in doubt choose the powerbank with the biggest available capacity.

### Wind turbine
To be able to recharge the power bank, there must be a wind turbine. This wind turbine must be operatable in wind, rain, snow and smoke. It should work in low and in high winds, as the environment may be unpredictable.

### Photovoltaic
In case if there is not enough wind, the propability of sunshine is quite high. So the power bank maybe recharged via small photovoltaic modules.
As they usually provide a output voltage of around 1,2 - 1,5 Volts, there must be four modules at least to reach the required voltage of a usual power bank (5 V).
If possible, there can be more photovoltaic modules to create a higher currency, so the power bank will be recharged faster.

### Power regulator
Power is nothing without control. So there has to be a power regulator that will take care, that the power bank is not overloaded and provided currency is as stable as possible. 

## SoC-Computer
A "**S**ystem **O**n a **C**hip" computer is the "brain" of C-Kit. For the beginning only a Raspberry Pi Model 3 will be supported with OS and all other software. 
As the Rapsi 3 is not the most actual version, it can be bought pretty cheap, which is an other important requirement.
On this Raspi 3 there will be a very small and highly customized OS to provide as many resources to the applications running on it AND even more important, to save as many power as possible.
The SoC computer must be protected from the environment, especially from heat, dust and dirt, rain, snow, hail and everything that might hit it. All to a sensible degree.

## GPS Module
The SoC must be able to read the GPS position of the C-Kit and transfer it to the other C-Kits. 
After it gets the confirmation, that its GPS position has been acknowledged by the command post, the GPS module may be turned off or put into standby to save power.
As soon as the SoC is operational the GPS module will be activated and the SoC has a task to gain the correct GPS position of it.
In case someone sends a SOS request via the C-Kit software, he doesn't have to worry about the correct GPS position. 


## Overall requirements

### CHEAP! CHEAP! CHEAP!
One very important thing is the price. No one will build C-Kits or at least not enough C-Kits, if they are too expansive. So they have to be cheap.

### Easy to build
If one needs a diploma in computer science and electronics, no one will build it. It should be so easy to build, that school clases can build, test and run some of them.

### Easy to run / operate
C-Kit must be very easy to run. Turn on power and let it run. That's it! If a C-Kit must be replaced, it shall take just a few minutes to get it up again.

### Light but reliable
A C-Kit should be as light as possible. So one person can at least four C-Kits over a long distance by feet. 
This makes it possible to deploy them in the field where no one but a human being can go to.

If it hits a tree|stone|wall|... while a person is on the way to deploy it, the C-Kit must not be damaged. If it falls down from a high of five meters, it must not be destroyed and still be operable.

### Resilliant to any environmental condition
The C-Kit must operate in heavy rain, storm, snow, smoke, hail, wind, heat, sunshine, darkness ... and any combination of it.
Yes, there might be an environmental condition that might break a C-Kit. That's bad and may break the communication chain, but that's life under hard conditions.
Then the

