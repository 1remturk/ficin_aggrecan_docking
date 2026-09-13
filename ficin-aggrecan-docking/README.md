# In-Silico Structural Evaluation of Ficin Proteolytic Targeting on Aggrecan G1 Domain

## Overview
Computational pipeline evaluating protein-protein docking between **Ficin** (*Ficus carica*, AlphaFold: P29714) and **Aggrecan G1 Domain** (PDB: 1N22), an extracellular matrix barrier limiting neural stem cell niche plasticity.

## Key Findings (Pose 15)
- **Binding Energy Proxy:** -3.74 kcal/mol
- **Favorable Contacts:** 17
- **Steric Clashes:** 0

### Interface Contacts (< 4.0 A)
- `MET1 (Ficin)` - `LYS584 (Aggrecan)` [2.36 A]
- `PRO24 (Ficin)` - `MET518 (Aggrecan)` [3.49 A]
- `ALA26 (Ficin)` - `ASN522 (Aggrecan)` [3.64 A]
- `SER3 (Ficin)` - `ARG242 (Aggrecan)` [3.99 A]

## Structure
- `data/`: Curated input PDBs
- `results/`: Docked complex PDB, contact maps, affinity plots

## ChimeraX Visualization
```text
color /A,B cyan
color /Z hotpink
surface
```
