# PKPD-IV-Infusion-Simulation: MATLAB simulation of IV infusion pharmacokinetics with effect-site PD model.

# IV Infusion PKPD Model – MATLAB

This project simulates the time course of drug concentration and effect for a constant-rate IV infusion, using a pharmacokinetic/pharmacodynamic (PKPD) model with an effect-site compartment. 
I developed this MATLAB script to demonstrate my ability to model biological systems, solve differential equations numerically, 
and create insightful visualizations.

## What I Built
- **Two-compartment PK model**: Central compartment (volume `V`, clearance `CL`) and effect-site compartment (rate constant `ke0`).
- **Infusion regimen**: Constant rate `R0` for duration `Tinf`.
- **PD model**: Sigmoidal Emax model (`Emax`, `EC50`, Hill coefficient `n`) linking effect-site concentration to drug effect.
- **ODE solver**: Used MATLAB’s `ode45` to simulate concentrations over 24 hours.
- **Visualization**: Generated three plots that together validate the model and illustrate key PKPD concepts.

## Key Features
- **Parameter-driven**: All parameters are easily adjustable at the top of the script.
- **Clear code**: Well-commented, with a local function defining the ODE system.
- **Diagnostic plots**:
  1. Time profiles of central concentration, effect-site concentration, and effect.
  2. Effect vs. central concentration (hysteresis loop) – shows the delay.
  3. Effect vs. effect-site concentration – collapses the loop, confirming the model.

<img width="560" height="338" alt="image" src="https://github.com/user-attachments/assets/7588166e-76fe-4be3-92ef-5f236bca716f" />


## Skills Demonstrated
- MATLAB programming (scripting, function writing, plotting)
- Numerical methods (solving ODEs with `ode45`)
- Pharmacokinetic/pharmacodynamic modeling
- Data visualization and interpretation
- Attention to detail (clear code structure, comments, parameter customization)

## How to Run
1. Open `IV_infusion_PKPD.m` in MATLAB (R2010b or later).
2. Click **Run** or type the filename in the Command Window.
3. Modify parameters at the top to explore different scenarios.

## Files
- `IV_infusion_PKPD.m` – main MATLAB script (all code in one file).


Feel free to reach out if you have questions or would like to discuss this project further.
