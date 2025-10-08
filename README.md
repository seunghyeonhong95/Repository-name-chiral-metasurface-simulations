# Simulation Data for Single-Layer Chiral Metasurface

This repository contains simulation files supporting the research published in Physical Review A.

**Paper Title:** Single-layer all-dielectric chiral metasurface with strong circular dichroism based on electric dipole resonances

**Authors:** S. H. Hong, S. Hong, Y. Kim, B. Kim, J. Lee, and S-H. Kwon

**Affiliation:** Department of Physics, Chung-Ang University, Seoul 06974, Korea

**Publication:** Physical Review A (2025)

---

## 📁 File Descriptions

### 1. S_parameter_Ellipticity.fsp
- **Software:** Lumerical FDTD Solutions
- **Purpose:** Calculates S-parameters and ellipticity of transmitted light
- **Structure:** Three dielectric cylinders (C1, C2, C3) on SiO₂ substrate
- **Key Parameters:**
  - Cylinder radii: r₁=180nm, r₂=205nm, r₃=230nm
  - Height: h=580nm
  - Unit cell period: a=1000nm
  - Wavelength range: 1400-1600nm

### 2. CD.fsp
- **Software:** Lumerical FDTD Solutions
- **Purpose:** Calculates circular dichroism (CD)
- **Method:** Transmission difference between LCP and RCP light
- **Key Results:** Maximum CD = 0.644 at 1520nm

### 3. mode_profile.mph
- **Software:** COMSOL Multiphysics
- **Purpose:** Electric field distribution analysis
- **Method:** Finite Element Method (FEM)
- **Visualization:** Normalized |E| in XZ cross-section

---

## 🔧 Requirements

### Lumerical FDTD Solutions

### COMSOL Multiphysics
- Version: 6.3
- Module: Wave Optics

## 📊 Key Results

- **Circular Dichroism (CD):** 0.644 at 1520nm
- **Optical Activity (OA):** 150°/λ
- **Structure:** Single-layer metasurface (thickness: 580nm)

---

## 📧 Contact
For questions or issues, please contact:

Corresponding Author: S-H. Kwon (shkwon@cau.ac.kr)
First Author: S. H. Hong (seunghyeon.hong95@gmail.com)

## 📄 License
MIT License 


## 📖 Citation

If you use these simulation files, please cite:
```bibtex
@article{Hong2025,
  author = {Hong, S. H. and Hong, S. and Kim, Y. and Kim, B. and Lee, J. and Kwon, S-H.},
  title = {Single-layer all-dielectric chiral metasurface with strong circular dichroism based on electric dipole resonances},
  journal = {Physical Review A},
  year = {2025},
  note = {(to be updated with volume/page upon publication)}
}


