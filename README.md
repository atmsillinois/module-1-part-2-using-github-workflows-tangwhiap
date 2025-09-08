# Freezing Probability for Fe<sub>2</sub>O<sub>3</sub> Aerosols

This repository provides a Python implementation of the **water-activity-based immersion freezing model**  
(*Knopf & Alpert, 2013*) for calculating the freezing probability of immersed Fe<sub>2</sub>O<sub>3</sub> aerosol particles.

The model computes:

1. Saturation vapor pressure over **water (e<sub>s</sub>)**
2. Saturation vapor pressure over _ice_ (e<sub>i</sub>)
3. Water-activity depression Δa<sub>w</sub>
4. Heterogeneous ice nucleation rate J<sub>het</sub>
5. Freezing probability P<sub>frz</sub> using the Poisson model

---

## ✨ Features

- Calculates freezing probability for immersed Fe~2~O~3~ aerosols
- Based on the **water-activity-based immersion freezing model**
- Input parameters:
  - Temperature **T** (Kelvin, *K*)
  - Exposure time *t* (seconds, *s*)
  - Particle diameter D<sub>p</sub> (meters, *m*)

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
