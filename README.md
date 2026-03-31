# Fanno Flow Solver for Pipe Systems

This Python script models compressible gas flow through a pipe system using the **Fanno flow model**. It computes Mach number, static and stagnation pressures, density, temperature, velocity, and mass flow rate at discrete pipe locations, while accounting for friction and pipe features such as bends.

---

## Features

- Supports multiple solver modes:
  1. **Maximum (choked) mass flow** for given system conditions
  2. **User-specified inlet Mach number**
  3. **User-specified inlet mass flow rate**
- Handles arbitrary numbers of pipe segments and features (e.g., bends) using equivalent lengths
- Computes for each pipe feature:
  - Static pressure
  - Stagnation pressure
  - Density
  - Temperature
  - Velocity
  - Mach number
  - Mach speed
  - Mass flow rate
  - Percentage pressure loss
- Uses numerical solvers (`fsolve`) for Fanno flow and Darcy friction factor calculations

---

## Dependencies

- Python 3.x
- [NumPy](https://numpy.org/)
- [SciPy](https://scipy.org/)
- [Matplotlib](https://matplotlib.org/)
- [SymPy](https://www.sympy.org/)

Install dependencies using pip:

```bash
pip install numpy scipy matplotlib sympy
```

## Author
Thomas Winn

Wisconsin Space Program (WISP)
