# The Impedance of an Antenna

## Antenna Impedance

As with any circuit element, the impedance of an atnenna presents to its source can be defined by the current that flows when a voltage is applied to it. There are, after all, no footnotes to Ohm's law that repeal it for the case of an antenna. Thus, for any possible connection point to an antenna, if we know the levels of current and voltage, Ohm's law will reveal the impedance at that point.

### Impedance of a Center-Fed dipole

The ratio of voltage to current, the impedance, will vary as you change any of the key dipole parameters. If you change the length through values around λ/2, the ratio will go through a point at which the ratio is resistive. This is also described as the *resonant point* - that is, there is no reactive component and thus the impedance is entirely resistive. This special length is referred to as the resonant half-wave dipole length. It is frequently used and encountered.

### Impedance of a Dipole in Free Space

We will begin by considering a thin dipole in free-space. At resonance it will have an impedance around 72 ohms. If you make the antenna slightly shorter (or a slightly lower frequency), it will look like a resistance in series with a small amount of capacitance. If you make it longer (or slightly higher frequency), it will look like a resistance in series with a small inductance.

A key parameter in determining both the impedance of a resonant dipole and how the impedance changes with frequency is the ratio of length-to-diameter. As the diameter increases, the impedance/resistance will slightly go down.

The following points should be observed:
1. As the conductor diameter increases, the length of the resonant dipole decreases. Note that in free space, λ/2 at 10MHz is 49.2 feet, compared to 47.81 feet for the wire case (about 97%) down to 45.98 feet for the very thick dipole (about 93.5%)
2. As the conductor diameter increases, the change in impedance with frequency decreases. This will be important in relation to wideband antennas.
3. If the source is designed to feed a resistive load, it is relatively simple to provide a match to it even if the antenna has a reactive component. For example, if we want to operate a 10MHz Length/Diameter = 1000:1 antenna on 10.1MHz, the inductive reactance component is +11.8 Ohms. By inserting a capacitor with a capacitive reactance of -11.8 Ohms at the antenna, you will present the source with a resistive load of 74.4 Ohms, almost the same as if we shortened the antenna to make it resonant.

### Impedance of a Dipole near Earth

Reflections from the ground couple to a dipole, much in the way a load on one winding of a transformer couples to another. This the impedance of a dipole will be different at different heights above the ground, depending on the magnitude and phase of the reflection - functions of ground characteristics and height above ground.

## Review Questions

4.1: Why might we care what the impedance of an antenna is?



4.2: What principle accounts for the difference in the effect of ground between horizontal and vertical antennas?

4.3: What might be the effect of connecting and antenna and transmitter with different impedances?

4.4: Describe advantages and disadvantages of thin and thick antennas as shown in figures 4-3 through 4.5.

### Notes trying to figure out questions above

Impedance via inductive reactance is caused by the swapping of directions in an AC circuit. The 'stored energy' opposes change, resulting in increased impedance. This is why higher frequency will have a higher inductive reactance, as the signal is changing more frequently causing more impedance.

Impedance via capacitive reactance is the opposition to AC current caused by a capacitor's charging behavior, which decreases as frequency increases (faster voltage change -> higher current means higher frequency is less impacted). Some cases where this is useful is high-pass filtering, where it blocks low frequencies and passes RF signals, or matching networks where it cancels inductive reactance and can be used to tune antennas.

Impedance is returned power to the source. A visual is here:
