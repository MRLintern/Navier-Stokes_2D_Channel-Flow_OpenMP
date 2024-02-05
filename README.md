### Navier-Stokes 2D Open Channel Flow Solver

## Introduction
This repository can be seen as an extention of the serial-version of the `NavierStokes-2D-ChannelFlow`.
This version incorporates multithreading via the OpenMP API and is developed in a 'modern' Object Oriented way, rather than the original procedural way.
I assume that the user/reader is familar with Fluid Dyanmics and therefore the **Navier-Stokes Equations**.
What I will go over is the **Linear Algebraic Solvers**: **Successive Over-Relaxation (SOR) Method** and the **Jacobi Iterative Method**.

## The SIMPLE algorithm

The Navier-Stokes Equations are solved via the *SIMPLE ALGORITHM*, a widely used numerical procedure in Computational Fluid Dynamics, where the acronym stands for:

* **S**: Semi-
* **I**: Implicit
* **M**: Method (for)
* **P**: Pressure
* **L**: Linked
* **E**: Equations

## Mathematics: Numerical Linear Algebra

### Successive Over-Relaxation Method

### Jacobi Iterative Method

## Requirements

* Software developed on `Ubuntu 20.04`.
* `Make`.
* `Fortran 90` and compiler `gfortran`.
* Text Editor; any will do.
* `OpenMP`.
* Knowledge of Fluid Dynamics.
* General knowledge of **Applied Mathematics**: e.g. **Numerical Linear Algebra** and **Numerical Partial Differential Equations**.

## Running the Application

* `$ git clone https://github.com/MRLintern/Navier-Stokes_2D_Channel-Flow_OpenMP.git`
