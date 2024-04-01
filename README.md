# Digital Control Projects
Course projects completed in key subjects in the field of Digital Control Systems

## Automation Control Theory Project
The purpose of the work is to synthesize a controller that provides specified quality criteria (transient response time, overshoot) in the presence of a reference signal and external disturbance.

In the process of performing the work, such properties as controllability and observability were applied, mathematical models of the reference and disturbing signals were determined, a reference model for the system was built, an observer for signals was calculated, and an extended error model was formed. Based on this, the required regulator was further constructed.

The calculation results were simulated in the Matlab/Simulink platform.

## Discrete Systems Control Project
The purpose of the work is to synthesize a discrete controller that provides specified quality criteria (transient response time, overshoot).

In the course of the work, a discrete P-regulator was synthesized, operating with a given quantization period. The reference model was calculated using a Newton polynomial of degree 3. The controller coefficients were calculated by solving the Sylvester equation.

The calculation results were simulated in the Matlab/Simulink platform.

## Adaptive and Robust Control Project
The purpose of the work is to synthesize an adaptive control law that compensates for an unknown disturbance using the Kreisselmeyer scheme, which provides accelerated parametric convergence.

During the work, the properties of controllability and observability were applied, a reference model based on the Newton polynomial was built, and parameters for the adaptation algorithm were calculated. The adaptation algorithm is based on the method using the Lyapunov function. Concepts such as a definite matrix and a strictly positive real function are used. Accelerated parametric convergence is ensured by selecting the transfer function L(c), after which an adaptive observer is formed for an unknown disturbance. Next, a comparison was made of the gradient adaptation algorithm with the Kreisselmeyer accelerated convergence algorithm.

The calculation results were simulated in the Matlab/Simulink platform.
