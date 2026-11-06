Frequency Control of a Power System Using PI Control and Solar PV

About the Project

This project was developed as part of our Control & Instrumentation course.

The idea behind the project is to understand how an electrical power system reacts when electricity demand or solar power generation changes, and how we can keep its frequency stable at 50 Hz.

We built a single-area power system model in MATLAB/Simulink, combining a conventional generator, governor, turbine, and solar PV generation. We then used a PI controller to bring the frequency back to its normal value whenever a disturbance occurred.

What We Worked On

Building a power system model in MATLAB/Simulink.

Understanding how generators, governors, and turbines work together.

Implementing a PI controller for frequency regulation.

Studying how changes in electricity demand affect system frequency.

Analyzing the impact of solar PV generation variations.

Checking system stability using the Routh-Hurwitz criterion.

Comparing the system response under different operating conditions.

PI Controller

We used a PI controller with the following parameters:

Kp: 1

Ki: 9.89387

The controller was designed to reduce frequency deviations and eliminate steady-state error.

Experiments

We tested the system under four different conditions:

Load Increase: What happens when electricity demand increases?

Load Decrease: How does the system respond when demand decreases?

PV Increase: What happens when solar power generation increases?

PV Fluctuation: How does the system react when solar generation first increases and then decreases?

These experiments helped us understand how different disturbances affect the frequency of the power system.

Results

The simulations showed that the PI controller was able to bring the system frequency back to 50 Hz in all tested scenarios.

Some of the main results:

Measurement

Result

Nominal Frequency

50 Hz

Maximum Frequency Deviation

0.0338 Hz

Settling Time

~10.7 seconds

Steady-State Error

0

System Stability

Stable

The system experienced small oscillations after each disturbance, but the frequency eventually returned to its nominal value.

Tools & Technologies

MATLAB

Simulink

Control Systems

PI Controller

Transfer Functions

Routh-Hurwitz Criterion

Team Members

Mihai Vlad

Perrick Noula Nbounga

Arda Deniz Gur

Destiny Imariabe

Enzo Drauli

Supervisor: Abdul Latif

This project gave us practical experience with control systems, mathematical modeling, and simulation. It also helped us understand how renewable energy sources, such as solar PV, can affect the behavior of an electrical power system.
