# The Field From a Dipole Near the Earth

## Phase of an Electromagnetic Wave

When talking about a circuit such as a standard household 120V, it's important to recognize that 120V is the root-means-square (RMS) or effective value of the sine wave. The actual voltage varies with time at a frequency of 60Hz, as seen below.

![120V AC Sine Wave.png](img.png)

If you measure the voltage at various times, you will measure an instantaneous voltage of anywhere between -170V and +170V. If you combine two such signals in a circuit that added the voltages, the result could range between -340V and +340V. If you add up two signals of the same phase, you end up with twice the voltage.

![240V sine wave.png](img_1.png)

In the other extreme, we could see one signal at it's maximum positive while the other is at its maximum negative voltage. In this case, the resulting net voltage would add up to 0V, as the signals would cancel eachother out. This would be known as a signal being exactly out of phase with the original signal.

Electromagnetic waves travel from an origin to a destination through multiple paths, especially through the ionosphere, and as a result exhibit all sorts of variations. Depending on the relative phase of the signals at the reception point, they could add, or could subtract from eachother. This is known as fading or signal enhancement (depending on if it helps or hurts the signal).

## What is the Effect of Ground Reflections?

A signal transmitted in any direction from an antenna near the Earth will have a direct path, and it will also have a path that results from the reflection from the surface of the Earth.

![img_2.png](img_2.png)

In the above, you can see that the direct path is shorter and wil first hit the receiving antenna, and then the reflected wave will hit shortly afterwards. 

![img_3.png](img_3.png)

In the above, we can see the example with an antenna elevated above the Earth broadcasting to a target in space.

For any elevation or takeoff angle there is a direct path from the antenna to the observer, and there is also a reflected path. The two paths have different lengths, with the reflected paht always longer than the direct path. The difference in length will depend how high above the Earth the antenna is and the elevation angle. 

As the downward wave strikes the Earth, the combination of the incident wave and reflected wave cannot create an electric field at the surface of the ground since fields can't exist in a perfectly conducting ground medium (they are shorted out by the ground). Therefore, for a horizontally polarized antenna the reflected wave must be out of phase with the incident wave.

Vertically polarized waves must have the reflected and incident waves in phase with eachother because opposite ends of the field are at the Earth's surface when they are in phase.

You can calculate the difference in path length fairly easily using plane geometry and trig, provided any takeoff angle and height. By combining this with a known signal frequency and speed of propagation (speed of light in air), you could easily compute the phase difference due to the different path and thus resultant amplitude. You can also use antenna modeling tools for the same.

Another way to visualize the reflected wave is to imagine it comes from another antenna under the Earth the same distance that the real antenna is above the Earth. This is called an image antenna and isn't real, but the path length difference is easier to visualize and calculate.

![img_4.png](img_4.png)
![img_5.png](img_5.png)

### How do the numbers add up?

Knowing the phase of the reflected wave and the height of the antenna, you can thus determine the resultant phase of the direct and reflected signals as a function of height. This just means you need to know the difference in path length in terms of wave lengths. For example, if the polarization is vertical, and the difference in path length is an odd multiple of a half wavelength, the signals will be out of phase and cancel at that angle. At other elevation angles, the difference may be an even number of half wavelengths and the signals will be the same phase and add together. For horizontally polarized antennas, it is the inverse. Intermediate (skewed) angles will have values in between the extremes.

You can determine the intensity of the combination of the two antennas by merely adding up the signals for each elevation and azimuth angle. You can also use tools such as EZNEC for this.

### Dipole over typical ground