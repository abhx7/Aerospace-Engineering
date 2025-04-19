# Notes

## Review of Fluid Mechanics

- Using Reynolds Transport Theorem (equations for compressible and incompressible flow)
  - Mass Conservation

    ![Equation](https://quicklatex.com/cache3/0e/ql_a662aea260a2a83407d104091e02210e_l3.png)
  - Momentum Conservation (Euler Equation for inviscid flows)
 
    ![Equation]()
  - Energy Conservation
 
    ![Equation]()

A local thermodynamic state is fixed by any two thermodynamic variables (P, T, s, rho)

First Law of Thermodynamics

Enthalpy equation

Heat capacities at constant volume (Cv) and constant pressure (Cp)

Maxwell's relations

## Acoustics 
= assume no viscous dissipation, hence isentropic flow
- pressure wave equation derivatioon through mass conservation and euler equations; similarly for velocity wave equation
- speed of sound relations

## Introduction
Shock

Mach number, Mach cone, Zone of Influence and Zone of Silence

Wave equations and causality - https://youtu.be/YWOeOi6q62s?si=9mzgQHopWJK-r9Np

Supersonic flow past an object - Compression Shocks and Expansion Waves

## Variable area flows 
Conservation of mass in a 'slice' 

$$\frac{\partial}{\partial x} (\rho u A)$$

- Use isentropic and 1D euler equation to show change in density and velocity with change in area depending on if it is supersonic or subsonic flow.
  ```math
  \frac{du}{u} = \frac{1}{1-M^2} \frac{dA}{A}
  ```
- If area is increasing, for subsonic flow, velocity decreases and density increases and vice versa for supersonic flow
- If area is decreasing, for subsonic flow, velocity increases and density decreases and vice versa for supersonic flow
- If no area change (at throat of the CD nozzle), at sonic speed there is a finite change in velocity, it is a Laval nozzle and if M is not equal to 1, there is no velocity change, it is a Venturi nozzle

Isentropic perfect gas relations among pressure, temperature and density between the static and stagnation quantites and for each with Mach number and specific gas constant.

Values of pressure and temperature ratios at sonic condition. Also the relation to area ratio.

Pressure drops as fluid flows through nozzle due to increase in M. When this hits a limit at infinity, there is a finite flow speed, the maximum possible (in an inviscid steady state flow) [Equation]. (2 ways to derive)

## Converging nozzle
Pressure ratio variation curves

## Bernoulli's for compressible flow

the equations, starting point of derivations and assumptions


## Rayleigh flow

## Fanno flow




## References

Gas Dynamics Notes Summary -  [This is a book of notes for the ME 461/561: Gas Dynamics course taught by Prof. Kyle Niemeyer at Oregon State University](https://kyleniemeyer.github.io/gas-dynamics-notes/intro.html)
 
    
 # Cool Stuff
 - [Shock diamonds in supersonic flow](https://www.linkedin.com/posts/sriram-aditya-b01868236_shockdiamonds-supersonicflow-aerospaceengineering-activity-7317377431772770304-CaFe/?utm_source=share&utm_medium=member_android&rcm=ACoAAD-ruCgBJnujmeLzmj1X4DpLLTuxktERedQ)
