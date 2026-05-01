# BB84 Monte Carlo QKD Simulation

This repository contains a simple Monte Carlo simulation of the BB84 quantum key distribution protocol. The simulation includes channel noise and an intercept-resend attack performed by Eve, and studies the dependence of the QBER, the estimated secret key fraction, and the final secret key length on the interception probability.

The secret key fraction is estimated using the idealized expression

$$
r = \max(0, 1 - 2h_2(Q))
$$

where $Q$ is the QBER and $h_2(Q)$ is the binary Shannon entropy.

This code was developed as part of the Bachelor's thesis:

**Introducción a la Información Cuántica y Computación Cuántica**  
Universidad Complutense de Madrid, 2025–2026.

## Files

- `BB84_TFG_Fisica.ipynb`: Jupyter Notebook containing the simulation, plots, and code.
