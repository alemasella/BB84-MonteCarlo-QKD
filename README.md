# BB84 Monte Carlo QKD Simulation

This repository contains a Jupyter Notebook with a Monte Carlo simulation of the BB84 quantum key distribution protocol. The simulation includes channel noise and an intercept-resend attack performed by Eve, and studies the dependence of the QBER, the estimated secret key fraction, and the final secret key length on the interception probability.

The secret key fraction is estimated using the idealized expression

$$
r = \max(0, 1 - 2h_2(Q))
$$

where $Q$ is the QBER and $h_2(Q)$ is the binary Shannon entropy.

This notebook was developed as part of the Bachelor's thesis:

**Introducción a la Información Cuántica y Computación Cuántica**  
Universidad Complutense de Madrid, 2025–2026.

## Files

- `BB84_TFG_Fisica.ipynb`: Jupyter Notebook containing the simulation, plots, and code.


## Output

The notebook generates four plots:

1. QBER as a function of Eve's interception probability.
2. Estimated secret key fraction as a function of Eve's interception probability.
3. Estimated final secret key length as a function of Eve's interception probability.
4. Theoretical secret key fraction as a function of the QBER, with the 11% security threshold.
