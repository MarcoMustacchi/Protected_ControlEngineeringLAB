<p align="center">
  <img src="https://github.com/MarcoMustacchi/MarcoMustacchi.github.io/blob/main/assets/img/icons/UniPD_logo.svg" width="150">
</p>

<h1 align="center"> (Protected) Control Engineering LAB - Laboratory Activities <br> UniPd</h1>

## Lab 0: Position PID–control of a DC servomotor 
<a href="https://github.com/MarcoMustacchi/Protected_ControlEngineeringLAB/raw/master/Lab0/report/Lab0RealMotor/ReportLab0RealMotor.pdf">📄Paper</a>
<br>
The goal of this laboratory activity is to design a position PID controller for the DC servomotor
available in laboratory. The design is carried out in frequency domain (i.e Bode’s method) with the
adoption of a nominal model of the motor, whose parameters are deduced from data–sheets. In
the second part of the activity, the values of the motor parameters, including the static and viscous
friction, are estimated with simple experimental tests. The parameters will be used in the next
laboratory activity to improve the control performances, in particular by implementing a feedforward
inertia plus friction compensation scheme.


## Lab 1: Position state–space control of a DC servomotor 
<a href="https://github.com/MarcoMustacchi/Protected_ControlEngineeringLAB/raw/master/Lab1/report/Celab_Report1.pdf">📄Paper</a>
<br>
This laboratory activity is articulated in two parts: in the first part, some improvements to the position
PID–control system designed in the previous laboratory activity are introduced. The improvements
consist in the implementation of an anti–windup scheme to reduce the large overshoot occurring
in the step response when the controller output saturates, and a friction plus inertia feedforward
compensator, which allows to enhance both the accuracy and speed of response of the conventional
feedback controller.
The second part of the activity is devoted to the design of a continuous–time position control
system by using state–space techniques. Both nominal and robust tracking designs are considered.
Nominal tracking is performed by exploiting a conventional feedforward scheme; on the other hand,
robust tracking is achieved by either exploiting an integral action (for robust tracking of constant
set–points, or perfect rejection of constant load disturbances), or by resorting to the internal model
principle (for robust tracking and perfect rejection of more general, possibly time–varying signals).


## Lab 2: Digital position control of a DC servomotor 
<a href="https://github.com/MarcoMustacchi/Protected_ControlEngineeringLAB/raw/master/Lab2/report/Celab_Report2.pdf">📄Paper</a>
<br>
The goal of this laboratory activity is to design a digital position controller for the DC servomotor
available in the laboratory. Two different design approaches are considered: in the design by emulation, 
the digital controller is obtained by discretization of a controller that is originally designed in
the continuous–time domain; vice versa, in the direct digital design (or discrete design), the control
design is performed directly in the discrete–time domain, using a discrete–time model of the plant
to be controlled.


## Lab 3: Position control of a DC servomotor with resonant load
<a href="https://github.com/MarcoMustacchi/Protected_ControlEngineeringLAB/raw/master/Lab3/report/Lab3Challenge/Group2_Tuesday_Lab3_Challenge.pdf">📄Paper</a>
<br>
The goal of this laboratory activity is to design a position controller for a DC servomotor driving
a resonant mechanical load. For such purpose, the original inertial load (disc inertia) of the DC
gearmotor available in laboratory is replaced with a rigid beam connected to the motor through a
flexible coupling (elastic joint). The whole setup actually resembles a conventional two–mass system,
which is the representative model of practically every motion system with an elastic transmission.
Both the PID and state–space control techniques are taken into account for the design. The state–
space design is performed with either conventional eigenvalues placement methods, or by using
optimal techniques based on the Linear Quadratic Regulator (LQR).


## Lab 4: Longitudinal state–space control of the balancing robot
<a href="https://github.com/MarcoMustacchi/Protected_ControlEngineeringLAB/raw/master/Lab4/report/Celab_Report4.pdf">📄Paper</a>
<br>
The purpose of this laboratory activity is to design and test a longitudinal state–space controller
for the two–wheeled balancing robot (also referred as “two–wheeled inverted pendulum robot”, or
“Segway–like robot”) available in laboratory. The controller is designed to simultaneously stabilize
the robot body to its upward vertical position, and the robot base to a desired longitudinal position
set-point. The design is performed by resorting to a simplified model of the robot dynamics, obtained
by assuming that the motion occurs along a straight line (i.e. the lateral or heading–angle dynamics
is ignored).

<br>

> All MATLAB script files are protected 
