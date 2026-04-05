# Atomic Structure from the Compact Fiber
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19426034.svg)](https://doi.org/10.5281/zenodo.19426034)

**Author:** A. R. Wells  
**Affiliation:** Dual-Frame Research Group  
**License:** CC BY 4.0  
**Contact:** No solicitation for correspondence or media contact  
**Paper email:** arwells.research@proton.me

---

## Overview

This repository contains the LaTeX source for the paper  
**_Atomic Structure from the Compact Fiber: Transport, Screening, and Spectroscopic Thresholds in the Reciprocal System_**.

The paper develops the first major physical application of the compact fiber established in the companion foundational paper:

- **Paper I:** *The Compact Fiber as the Canonical Admissibility Structure for Discrete Scalar Motion*

The present paper treats the **stable local atomic and spectroscopic regime**. Its central result is that key atomic screening quantities are not empirical inserts, but are generated mechanically from the compact fiber’s transport and readout geometry.

---

## Core Idea

The paper argues that the compact fiber is not merely an abstract admissibility object. In the atomic regime, it is **materially organizing**.

Its primary result is the **Class II screening classification**:

- all 11 screening slopes and intercepts for ionization energy, electron affinity, fine-structure splitting, and electric polarizability are generated from the fiber capacities
  - \(N_m = 4\)
  - \(N_e = 8\)
- no per-element fitted parameters are used
- the classification is **cross-constrained**: a single error in the fiber capacities would break all 11 quantities simultaneously

Building on this classification, the paper develops:

- a **Class I restoration-depth law**
  \[
  n_{\mathrm{eff}} = \frac{\mathrm{period} + e + 42}{16}
  \]
- a **time-region / Kustaanheimo--Stiefel bridge** recovering the hydrogen Rydberg spectrum
- a **quantum-defect threshold**
  \[
  ab > \ell(\ell+1)
  \]
  reproducing the periodic-table group structure

---

## What This Paper Demonstrates

The paper shows that:

1. **Atomic screening structure is mechanically generated from the compact fiber**  
   The 11 Class II quantities are not fitted one by one; they arise from the three readout classes, the inner-shell readout structure, and the fiber capacities.

2. **Atomic depth structure can be organized from the same fiber geometry**  
   The restoration-depth law and related shell/depth structure are presented as structural consequences of the compact fiber under the adopted depth model.

3. **Spectroscopic threshold structure follows from displacement organization**  
   The threshold law \(ab > \ell(\ell+1)\) recovers the onset structure behind the \(s/p/d/f\) channel pattern and periodic-table group sizes.

4. **The mature empirical core is parameter-light and auditable**  
   In the mature core, the framework produces about 95 atom-observable comparisons at about 5.7% weighted mean absolute error, with zero per-element fitted parameters.

---

## What This Paper Does *Not* Claim

- It does **not** claim that the later spectroscopic and time-region results are proved at the same closure level as the Class II screening classification
- It does **not** claim that the inner-shell readout model, second-power inter-regional relation, or \(K_{G1} \propto ab\) proportionality have already been shown to be uniquely forced within the framework
- It does **not** claim a fully closed derivation of the quantum-defect normalization constant \(C\)
- It does **not** treat Hilbert-space emergence, the Born rule, or Bell correlations
- It does **not** rely on Slater screening rules, the Aufbau principle, shell capacities \(2n^2\), or the Coulomb potential as primitive inputs

Instead, it presents the atomic regime as the first major physical readout of the compact fiber, while keeping the remaining modeling assumptions and open constants explicit.

---

## Empirical Status

The paper distinguishes a **mature core** from the broader program.

### Mature core
- Ionization energy
- Fine-structure splitting
- Electric polarizability
- Electron affinity

### Current mature-core result
- **~95 atom-observable comparisons**
- **~5.7% weighted mean absolute error**
- **zero per-element fitted parameters**

### Full current program
- **~119 total comparisons**
- includes extensions and one bootstrap family

### Open global constant
- quantum-defect normalization constant  
  \(C \approx 0.361\)

---

## Repository Contents

- `paper/atomic_structure_compact_fiber.tex` — master LaTeX source
- `paper/atomic_structure_compact_fiber.pdf` — compiled paper PDF

---

## Build Instructions

Requirements: `latexmk` with a standard LaTeX installation.

Build the paper:

    cd paper
    latexmk -pdf -interaction=nonstopmode -halt-on-error atomic_structure_compact_fiber.tex

Clean build artifacts:

    cd paper
    latexmk -C

The compiled PDF will be located at:

    paper/atomic_structure_compact_fiber.pdf

---

## Relationship to the Companion Paper

This paper depends on the compact-fiber structure established in Paper I and should be read as its first major physical sequel.

**Paper I provides:**
- the compact fiber
- the covering map
- the transport metric
- the readout classification
- faithful displacement placement

**This paper provides:**
- atomic screening classification
- restoration-depth structure
- spectroscopic threshold structure
- empirical confrontation in the atomic regime

---

## Status

- Compact-fiber atomic sequel completed
- Class II screening classification established as the paper’s primary result
- Class I restoration-depth law developed
- Time-region / KS spectroscopic bridge developed
- Threshold structure for \(s/p/d/f\) channel onset developed
- Mature-core empirical comparison completed
- One open global normalization constant remains

Recommended citation:

A. R. Wells (2026).
*Atomic Structure from the Compact Fiber: Transport, Screening, and Spectroscopic Thresholds in the Reciprocal System* (v1).
Zenodo. 10.5281/zenodo.19426035

---

## Citation

If you use or reference this work, please cite the Zenodo record corresponding to the version used.

Recommended citation:

A. R. Wells (2026).
*Atomic Structure from the Compact Fiber: Transport, Screening, and Spectroscopic Thresholds in the Reciprocal System* (v1).
Zenodo. 10.5281/zenodo.19426035

This work is released under Creative Commons Attribution 4.0 (CC BY 4.0).