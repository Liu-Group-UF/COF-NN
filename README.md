# COF-NN

COF-NN is a neural-network interatomic potential designed for 2D covalent organic frameworks (COFs) and intended to be used through the **FLAME** package.

This repository provides:
- A trained COF-NN model file (to be placed in the proper location for FLAME).
- The required FLAME input files (YAML / parameter files).
- Example configurations to run common tasks.

---

## 1) Prerequisites

You must first install **FLAME** on your machine:

- FLAME GitHub: https://github.com/flame-code/FLAME  
- FLAME Documentation (keywords & input options): https://flame-code.gitlab.io/FLAME/index.html

> The meaning of directives in the FLAME input file can be found in the official FLAME documentation.

---

## 2) Files you need

To run COF-NN with FLAME, prepare the following files:

- **FLAME input**: `flame_in.yaml`  
- **Element/type mapping & ANN parameters**: `elements-type.ann.param.yaml`

Once these files are ready, you can run FLAME directly.

## Acknowledgements

This project relies on the **[FLAME](https://github.com/flame-code/FLAME)** framework. We sincerely thank the FLAME developers for building the FLAME environment and providing comprehensive documentation and tooling that make this work possible.

We also acknowledge the developers and the broader community behind the **[Behler–Parrinello neural network (BPNN)](https://doi.org/10.1103/PhysRevLett.98.146401)** architecture.

