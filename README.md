# Asymmetric Noncommutative Torus has vanishing Einstein tensor [arXiv:2511.15539]

## Overview

Mathematica calculations and supporting code for research on the geometry of the asymmetric noncommutative torus.

## Contents

- `notebooks/` — Mathematica notebooks containing calculations and derivations.
- `src/` — reusable Wolfram Language source files.
- `results/` — selected research outputs, where appropriate.

## Requirements

- Wolfram Mathematica
- NCAlgebra package

## How to use

Open the relevant `.nb` notebook in Mathematica. If a calculation uses a `.wl` file, load it from the notebook using `Get` or `Needs` as appropriate.
- Uncomment the following command (`PacletInstall[...]`) and run it once to install the NCAlgebra package when using the notebook for the first time. After installation, comment it out again to avoid reinstalling the package on subsequent runs. Once NCAlgebra is installed, this step does not need to be repeated for other .nb files.

## Notes

- Check the results folder in the main branch and run `Asymmetric torus Einstein Functional F(A, B).nb` to obtain all the terms of the Einstein functional before integration.
- Run `Einstein Functional Integral.nb` to integrate each (F(s,m,n,\beta,A,B)) as a rational function of (s), and then sum the results to verify that the total is zero.
- The `src` folder contains independent mathematical code for computing torsion and metric functionals, provided for further exploration.
- The `notebooks` folder contains smaller programs developed to test the algorithm's functionality and experiment with different operations using the NCAlgebra package.