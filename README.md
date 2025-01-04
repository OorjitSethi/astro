
# Orbital Dynamics Scripts

This repository contains two Python scripts, `HohmannTransferOrbit.py` and `KeplerTrueAnomaly.py`, both of which deal with concepts in celestial mechanics and orbital dynamics.

## Files Overview

### 1. `HohmannTransferOrbit.py`

This script simulates a **Hohmann transfer orbit**, which is a two-step orbital maneuver used to transfer between two circular orbits. It employs visualization and animation to demonstrate the transfer sequence.

#### Key Features:
- **Physical Constants and Initial Conditions**:
  - Gravitational constant (G) and solar mass (M) are defined.
  - Initial orbital parameters such as radius and eccentricity are specified.
- **Mathematical Calculations**:
  - Conversion between astronomical units (AU) and meters.
  - Simulation of the transfer process using physical equations.
- **Visualization and Animation**:
  - Uses `matplotlib` to plot the orbits and animate the transfer sequence.
  - Animates key phases: pre-burn, burn, and post-burn.
- **Interactive Features**:
  - Widgets for user input (e.g., adjusting orbital parameters).

#### Dependencies:
- `numpy` for numerical computations.
- `matplotlib` for plotting and animation.

#### How to Use:
1. Install the required dependencies using `pip install numpy matplotlib`.
2. Run the script with `python HohmannTransferOrbit.py`.
3. Follow on-screen instructions to interact with the visualization.

---

### 2. `KeplerTrueAnomaly.py`

This script calculates and visualizes orbital dynamics based on **Keplerian motion**, focusing on the true anomaly. The true anomaly is the angular position of a body along its orbit at a specific time.

#### Key Features:
- **Orbital Parameters**:
  - Eccentricity, semi-major axis, and focus distance are hardcoded for a predefined orbit.
- **Mathematical Calculations**:
  - Calculates the orbital period using Kepler's Third Law.
  - Computes orbital velocities and geometry.
- **Visualization**:
  - Uses `matplotlib` to plot the orbit and illustrate key elements such as the semi-major and semi-minor axes.
- **Customizable Parameters**:
  - Users can modify the orbital parameters (e.g., eccentricity and semi-major axis) directly in the script.

#### Dependencies:
- `numpy` for mathematical computations.
- `matplotlib` for plotting.

#### How to Use:
1. Install the required dependencies using `pip install numpy matplotlib`.
2. Run the script with `python KeplerTrueAnomaly.py`.
3. Observe the orbital visualization and calculations.
