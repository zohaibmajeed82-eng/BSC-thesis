# Experimental and Numerical Investigation of Rotary Friction Welding of AISI 1045 Steel at Different Rotational Speeds (900, 1200, 1600 rpm)

**B.Sc. Final Year Project** · Department of Metallurgical & Materials Engineering, University of Engineering & Technology, Lahore

**Authors:** Muhammad Zohaib Majeed (2022-MM-20), Hafiz Ahmad Bilal (2022-MM-01)
**Supervisor:** Prof. Dr.-Ing. Furqan Ahmed · **Co-Supervisor:** Dr.-Ing. Muhammad Zubair

---

## 📄 Documents
- **[Full Thesis (PDF)](Thesis_fyp_RFW_2022_01,22mm20_finalcopy.pdf)**
- **[Presentation Slides (PDF)](thesis slides.pdf)**
## Overview
This work studies how rotational speed affects the microstructure and mechanical behaviour of
rotary friction welded (RFW) AISI 1045 steel joints. We combined experiments with a multiscale
computational approach that runs from the welding machine down to the atoms.

**Main finding:** **900 rpm** gave the best strength–ductility balance. **1600 rpm** gave the
hardest but most brittle weld. Higher speed gives a hotter interface and a faster self-quench,
which traps carbon and promotes bainite/martensite.

## Methodology
| Scale | Method | Purpose |
|---|---|---|
| Experimental | Tensile, guided-bend, nanoindentation, metallography | Joint strength, ductility, hardness, failure modes |
| Materials data | JMatPro | Temperature-dependent properties of AISI 1045 |
| Continuum | Coupled thermo-mechanical FE model (Abaqus) | Interface temperature history and cooling rates |
| Atomistic | Molecular dynamics with ML interatomic potentials (MatterSim, MACE, CHGNet) | Phase stability and elastic response of weld-zone phases |
| Quantum | DFT (Quantum ESPRESSO): Bain-path scan, climbing-image NEB | Martensite metastability, carbon migration barrier |

## Key Results
- **900 rpm (optimum):** highest UTS (~1380 MPa), fracture strain close to the base metal, and the full bend angle passed without cracking
- **1200 rpm:** intermediate, transitional behaviour; cracked away from the weld centreline
- **1600 rpm:** highest hardness and reduced modulus, lowest ductility, cracked at the weld interface at the lowest bend angle
- **FE simulation:** peak interface temperatures of ~980–1300 °C, with faster heating and cooling at higher speeds
- **DFT:** martensite (c/a ≈ 1.02) lies on a declining energy slope, so it is a kinetically trapped, metastable structure
- **NEB:** carbon migration barrier Eₐ = 0.724 eV, in agreement with literature values

No single method could answer the research question alone. Hardness data, FE-predicted cooling
rates and atomistic energetics together give one consistent explanation of how rotational speed
controls weld-zone phases and joint properties.

## Repository Structure
```
├── thesis/   Full thesis (PDF)
├── slides/   Presentation slides (PDF)
└── README.md
```

## Contact
Muhammad Zohaib Majeed · <zohaibmajeed82@gmail.com>

---
©Muhammad Zohaib Majeed. All rights reserved.
