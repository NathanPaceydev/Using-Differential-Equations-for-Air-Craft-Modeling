# Using Non-Homogenous-Differential-Equations For Air-Craft Simulation and Optimization
Programs taking two different approaches to choosing which damper to put on an air-craft given certain parameters. Amplitude.ipynb rearranges the equation to solve for the amplitude given a certain dampening value while DifferentialEquationsVisualizer.ipynb just displays the actual plots and calculates the amplitude more qualitatively (using the basic definition of amplitude.

## Given a system of differential Equations...
## Find the ideal damper given a frequency range
### Program designed to solve the second order non homogenous differential equation

A differential equation for θ (for θ small enough so that
sin θ ∼ θ is a good approximation) in this scenario is
given by
![image](https://user-images.githubusercontent.com/64051575/136565392-28ff83b7-4838-446c-a45f-de1bea34a393.png)

In a Rolls-Royce Trent 900 Series engine, used on Airbus
A380s, we know that
(a) the dry weight m of the engine is 6,246 kg,
(b) the distance L from the wing to the center of mass
is 5.48 m, and
(c) the damping coefficient is c = 104 N·m·s .

The design concern is that vibrations from the operation of the plane will result in practical
resonance, or large sympathetic vibrations, in the engine support. Specifically, vibrations
of the engine will produce torques on the engine support at a frequency of 9,000-12,000 RPM.
You have been assigned the task of choosing the stiffener for the engine support, which
essentially lets you choose the value of k in the model. You can choose among 6 stiffeners,
with k = 2, 3, 4, 5, 6 or 7 (1010 N)/m (1010 N). The goal is to minimize the amplitude
of the steady-state vibrations/swings of the engine, given the frequencies of the
applied vibrations from the engine.

Snippet From Amplitude.ipynb

![image](https://user-images.githubusercontent.com/64051575/134822052-9912aba2-8962-4bd3-af0e-2ba8ee2172fc.png)

Snippet From DifferentialEquationsVisualizer.ipynb

![image](https://user-images.githubusercontent.com/64051575/134822076-39583311-903a-471e-89be-2430c14a2b1d.png)

