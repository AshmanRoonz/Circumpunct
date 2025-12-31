# Circumpunct CPU (⊙-Core)

**Fractal Interface Quantum Computing Architecture**

*The Sierpinski Filter: A Novel Approach to Classical-Quantum Hybridization*

---

## Overview

This directory contains the complete specification, simulations, and visualizations for the **⊙-Core** architecture—a fractal-based computational primitive that bridges classical and quantum computing through self-similar boundary structures.

The key innovation is the **Sierpinski Filter**: rather than treating the classical-quantum boundary as a sharp wall (causing decoherence), we distribute the transition across a fractal interface where amplitude decays as φ⁻ⁿ (golden ratio scaling).

### Core Principles

- **Golden Amplitude Decay**: Signal amplitude follows A_n = φ⁻ⁿ at fractal depth n
- **Distributed Decoherence**: Errors spread across levels instead of concentrating at measurement
- **Bounded Error**: Total error < φ³ × ε_local ≈ 4.24 × ε_local (proven theorem)
- **Computational Universality**: Standard logic gates (AND, OR, XOR, NOT) via interference

---

## Contents

### Specifications

| File | Description |
|------|-------------|
| [sierpinski-filter-spec.md](sierpinski-filter-spec.md) | Formal mathematical specification with gate definitions, theorems, and proofs |
| [substrate-research.md](substrate-research.md) | Physical implementation survey: photonic crystals, superconducting resonators, topological insulators, etc. |
| [fractal-interface-quantum-computing-paper.md](fractal-interface-quantum-computing-paper.md) | Academic paper draft for submission |

### Simulations

| File | Description |
|------|-------------|
| [sierpinski_sim.py](sierpinski_sim.py) | Python numerical validation of amplitude decay, error bounds, and gate operations |

### Interactive Visualizations

| File | Description |
|------|-------------|
| [circumpunct-core.html](circumpunct-core.html) | Interactive ⊙-Core visualization with fractal architecture (p5.js) |
| [circumpunct_computer.html](circumpunct_computer.html) | Full computational architecture demonstration |
| [sierpinski-simulator.html](sierpinski-simulator.html) | Logic gate simulator showing interference-based computation |
| [sierpinski-figures.html](sierpinski-figures.html) | Publication-ready figures and charts (Chart.js) |

---

## Quick Start

### Run the Python Simulation

```bash
python sierpinski_sim.py
```

This validates:
- Amplitude decay profile (φ⁻ⁿ)
- Error bound theorem (ε < φ³ × ε_local)
- Logic gate correctness (AND, OR, XOR, NAND, NOR, XNOR)
- Regime transitions (Classical → Mixed → Quantum)

### View Interactive Visualizations

Open any `.html` file in a browser to explore:
- `circumpunct-core.html` — Watch the fractal boundary in action
- `sierpinski-simulator.html` — Test logic gates through the filter
- `sierpinski-figures.html` — View numerical validation charts

---

## Architecture Summary

```
Classical Input (A = 1)
       │
       ▼
   ┌───────────────┐
   │  CONVERGENCE  │  ≻ (gimel)
   │  φ⁻¹ → φ⁻² →  │  Amplitude decays
   │  → φ⁻³ → ...  │  Paths branch (3ⁿ)
   └───────┬───────┘
           │
           ▼
   ┌───────────────┐
   │   APERTURE    │  i (rotation)
   │   Phase: 90°  │  Quantum interference
   │   f(input)    │  Logic computed here
   └───────┬───────┘
           │
           ▼
   ┌───────────────┐
   │   EMERGENCE   │  ⊰ (beth)
   │  ... → φ⁻²  → │  Amplitude rebuilds
   │  → φ⁻¹ → 1    │  Paths coalesce
   └───────┬───────┘
           │
           ▼
Classical Output (A = 1)
```

**Master Equation**: Φ' = ⊰ ∘ i ∘ ≻[Φ]

---

## Key Results

### Amplitude Profile

| Depth n | A_n = φ⁻ⁿ | Regime |
|---------|-----------|--------|
| 0 | 1.000 | Classical |
| 1 | 0.618 | Mixed |
| 2 | 0.382 | Mixed |
| 3 | 0.236 | Approaching Quantum |
| 5 | 0.090 | Quantum |
| ∞ | 0 | Pure Quantum |

### Error Comparison

| Architecture | Parallelism | Error Rate | Interface |
|--------------|-------------|------------|-----------|
| Classical | 1 | 10⁻¹⁵ | N/A |
| Quantum (n qubits) | 2ⁿ | 10⁻³ | Sharp (problematic) |
| **Sierpinski (depth d)** | **3ᵈ** | **~10⁻⁸ (projected)** | **Fractal (gradual)** |

### Recommended Substrates

1. **Photonic Crystals** (★★★★★) — Room temperature, exact fractal geometry
2. **Superconducting Resonators** (★★★★★) — Highest quantum fidelity
3. **NV Centers in Diamond** (★★★★) — Room temperature quantum coherence

---

## Theoretical Foundation

The Sierpinski Filter emerges from the Circumpunct Framework's tripartite structure:

$$\odot = (\bullet, \Phi, \circ)$$

- **•** (center) = Classical/discrete
- **Φ** (field) = Quantum/continuous
- **○** (boundary) = Fractal/self-similar interface

The boundary is not a wall—it is a lens that makes the same system appear classical at one scale and quantum at another.

---

## References

- [Sierpinski Filter Specification](sierpinski-filter-spec.md) — Full mathematical formalism
- [Substrate Research](substrate-research.md) — Physical implementation options
- [Academic Paper](fractal-interface-quantum-computing-paper.md) — Prepared for submission

---

*"The boundary is not a wall. It is a lens."*
