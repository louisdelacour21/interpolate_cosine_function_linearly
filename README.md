# interpolate_cosine_function_linearly
# Linear Interpolation of the Cosine Function in Fortran

## Overview

This project implements a linear interpolation of the cosine function using Fortran. It was developed as part of the *Financial Markets* course at Universität Regensburg to gain familiarity with numerical methods and interpolation techniques applicable in computational finance.

## Objective

The main goal is to approximate the cosine function, \(\cos(x)\), over the interval \([0, 2\pi]\), using a piecewise linear interpolation method. This helps understand the trade-offs between computational simplicity and approximation accuracy in numerical analysis.

## Features

- Constructs a grid over the interval \([0, 2\pi]\)
- Computes exact cosine values at discrete points
- Performs linear interpolation to estimate values between the grid points
- Outputs both interpolated and true values for comparison

## Files

- `interpolate_cosine_function_linearly.f90` – Main Fortran source file containing the implementation.

## Requirements

- Fortran compiler (e.g., `gfortran`)

## How to Run

1. **Compile the program:**

   ```bash
   gfortran -o interpolate interpolate_cosine_function_linearly.f90
