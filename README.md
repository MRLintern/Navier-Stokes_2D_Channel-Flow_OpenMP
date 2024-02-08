# Navier-Stokes 2D Open Channel Flow Solver

## Introduction
This repository can be seen as an extention of the serial-version of the `NavierStokes-2D-ChannelFlow`.
This version incorporates multithreading via the OpenMP API and is developed in a 'modern' Object Oriented way, rather than the original procedural way.
I assume that the user/reader is familar with Fluid Dyanmics and therefore the **Navier-Stokes Equations**.
What I will go over is the **Linear Algebraic Solvers**: **Successive Over-Relaxation (SOR) Method** and the **Jacobi Iterative Method**.
I won't be focussing solely on Fortran like I did with the original solver. This time I will look using other languages too.
For example:

* `Modern C++`.
* `C`.
* `Python`.
* `Rust`.

### Note

This is a work in progress so it will take time to complete as I will be covering multiple languages.
At present, the solver is being developed in Fortran.

## The SIMPLE Algorithm

The Navier-Stokes Equations are solved via the *SIMPLE algorithm*, a widely used numerical procedure in Computational Fluid Dynamics, where the acronym stands for:

* **S**: Semi-
* **I**: Implicit
* **M**: Method (for)
* **P**: Pressure
* **L**: Linked
* **E**: Equations

## Mathematics: Numerical Linear Algebra

### Successive Over-Relaxation Method

To be completed.

### Jacobi Iterative Method

To be completed

## Requirements

* Software developed on `Ubuntu 20.04`.
* `Make`.
* `CMake`.
* `C++`.
* `C`.
* `Fortran`.
* `Rust`.
* `Python 3.x`.
*  Compiler for Modern `C++` and `C`; e.g. `g++/gcc 13.1.0` or `clang-10`.
*  Compiler for Fortran: e.g. `gfortran`.
* Text Editor; any will do.
* `OpenMP`.
* Knowledge of Fluid Dynamics.
* General knowledge of **Applied Mathematics**: e.g. **Numerical Linear Algebra** and **Numerical Partial Differential Equations**.

## Running the Application

* `$ git clone https://github.com/MRLintern/Navier-Stokes_2D_Channel-Flow_OpenMP.git`
