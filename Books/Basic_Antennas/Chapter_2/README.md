# Chapter 2: The Half-Wave Dipole Antenna in Free Space

### What is *free space*?

An antenna in free space is an extreme case where your antenna is considered the only object in the universe. This is a good way to think of antennas because it helps focus on just the functionality of the antenna vs the impact of the environment.

## The Half-Wave Dipole

The half-wave dipole is an antenna with 2 poles that are each λ/4 long (1/4 wavelength), meaning the total length of the antenna is λ/2, a "half-wave".

As with other antennas - a dipole antenna requires alternating current.

Many other antennas are made up of combinations of λ/2 dipole antennas in various configurations.

![dipole layout](img.png)

The figure above shows the layout of a λ/2 dipole antenna. The circle in the center represents a generator that is generating a signal at the operating frequency *f*. The total length of the conductor from end-to-end is approximately λ/2.

The distance of one wavelength in free space is the speed of light (*c*) multiplied by the time it takes to make a complete cycle. The time for one cycle is the waveforms **period** or 1/*f*. Thus, a wavelength in free space is given by the following formula: **λ = c/f**

For example, if c is in meters per second, and f is in Hertz (cycles per second), then λ will be in meters. To demonstrate with numbers, if you have a frequency of 10MHz, you have λ = 300,000,000 m/s divided by 10,000,000 Hz, which means λ = 30 meters. When using MHz, it may be convenient to just set c to 300, and totally cancel out the six zeroes for the million in c and MHz.

## So how does a dipole work?

![dipole current and voltage.png](img_1.png)

A key to understanding a dipole is looking at the "boundaries" or end points, where some conditions exert themselves. Physicists call these *boundary conditions* because they occur at the boundary between regions. In a dipole, the boundary exists between the conducting wire and the free space at each end of the dipole.

The condition is that there can be no current flow at the end of a conductor, because there is nowhere for the current to go. If there is power being supplied to this conductor, then λ/4 back from where the current is 0, the current must be at its maximum, as seen represented by the blue in the diagram above.

In conjunction with the current, if there is no current at the end of the antenna then the voltage must be at it's maximum. Inversely, the minimum voltage will be found closest to the generator. This can be seen in the graphic above as the red components of the diagram.

The power the generator puts into the antenna will be transformed from an electrical signal into a radiated electromagnetic wave.

![electric and magnetic fields perpendicular.png](img_2.png)

The antenna power will be the current at the center multiplied by the voltage at the center, which is the current and voltage supplied by the generator. Ohm's law, as with any other circuit, defines this relationship.

![ohms law](img_3.png)

Note that the feed point of the dipole is just an electrical circuit, with connections going to the antenna from the generator. In *free space*, you find that the voltage at that point is 73 times the current. Thus, the generator sees a load that looks like a resistor of 73 Ohms = V/I

## Where does the power go?

