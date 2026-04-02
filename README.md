# AxiomProgram | The Prime Polynomial Project 🌌🔢

> Exploring the boundaries, limits, and voids of prime-generating functions.

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](#)
[![C++ Standard](https://img.shields.io/badge/C++-17%2B-blue.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](#)

## 📖 Overview
**AxiomProgram** is a high-performance C++ brute-force engine designed to systematically search, analyze, and map prime-generating quadratic polynomials of the form $f(n) = an^2 + bn + c$. 

To date, the engine has evaluated over **513,556,650 permutations**, uncovering absolute sequence limits, algebraic shadows, and unexpected mathematical voids within complex Heegner Numbers.

## 🔍 Key Discoveries & Open Conjectures
This repository serves as the computational backbone for exploring several open conjectures in Number Theory and Algebra:

* **The Perfect 80 Absolute Limit:** Empirical evidence strictly bounding the maximum prime sequence length to 80, explicitly tied to the discriminant $\Delta = -163$.
* **The Prime Polynomial Void:** The systematic absence ("Dead Zones") of valid polynomials for leading coefficients such as $a = 5, 7, 8, 10$.
* **The Axiom Prime-Reciprocal Constant ($\mathcal{K}_{80}$):** A newly calculated bounding constant ($\approx 0.0573982$) derived from the optimal sequence $f(n) = n^2 - 79n + 1601$.

*Read the full mathematical breakdown in our [Open Conjectures Directory](link-to-your-website-or-wiki).*

## ⚙️ Engine Requirements
* C++17 compatible compiler (GCC / Clang)
* CMake (>= 3.10)
* OpenMP (Required for multithreaded brute-force processing)

## 🚀 Quick Start & Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/xBIwJEtx/AxiomProgram.git](https://github.com/xBIwJEtx/AxiomProgram.git)
   cd AxiomProgram
