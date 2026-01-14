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
