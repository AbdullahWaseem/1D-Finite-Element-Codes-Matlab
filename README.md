# One-Dimensional Finite Element Codes

## Context

This repository consists of one-dimensional finite element codes. To learn the basics of a subject, during my Ph.D., I use to derive all the equations and write a simple finite element code to run some tests. The experience gained during that stage greatly helped me when I had to extend it towards more complicated theory, complex geometry and two-dimensional cases. I hope someone who has just started the graduate studies would greatly benifit from these simple implementations.

## How to use the code?

Students who have been through an introductory course on finite element method can easily understand the content of the code. Examples for different physical phenomena are implement and can be run for

- steady-state heat transfer : `HeatTransfer_Linaer.m`
- transient heat transfer - with generalized-theta method   : `HeatTransfer_Linear_Transient.m`
- non-linear steady-state heat transfer : `HeatTransfer_NonLinear.m`
- non-linear transient heat transfer - with Euler back time integration : `HeatTransfer_NonLinear_Transient.m`
- thermo-mechanics -- with Gamma time integration : `ThermoMechanics_GammaMethod.m`
- thermo-mechanics -- with Newmark time integration : `ThermoMechanics_NewMark.m` 

Any bugs, comments, suggestions, and discussion on the theoratical and implementation aspect are highly appreciated.

## Disclaimer
This code is purely for educational purposes. All rights are preseved, however, author shall not be liable in any event caused by the use of the code. 
