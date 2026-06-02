# Navier-Stokes and Heat Transfer Simulation with FreeFEM++

## Overview

This project implements a finite element solver for the incompressible Navier-Stokes equations coupled with a convection-diffusion equation for temperature.

The numerical method uses:

- Implicit Euler time discretization
- Taylor-Hood finite elements (P2-P1)
- FreeFEM++
- Convection-diffusion coupling

---

## Mathematical Model

### Navier-Stokes equations

du/dt + (u · ∇)u = -∇p + νΔu

∇ · u = 0

### Temperature equation

dθ/dt + u · ∇θ - (1/Pe)Δθ = 0


---

## Numerical Method

- Finite Element Method
- P2 approximation for velocity
- P1 approximation for pressure
- P2 approximation for temperature
- Implicit Euler scheme

---

## Software

- FreeFEM++
