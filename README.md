# Pore Electric Field

This repository contains an initial (and currently inefficient) implementation for computing the electric field inside a porin membrane,  
especially for porins with an internal electric field in the so-called constriction region (e.g., OmpC/OmpF).  
The method is based on the approach described in the following publication:

> **Macroscopic electric field inside water-filled biological nanopores**  
> https://www.ncbi.nlm.nih.gov/pubmed/26931352

## Requirements

The program takes the following input files:

- `*.tpr` — Topology and simulation parameters  
- `*.xtc` — Molecular dynamics trajectory  

## Python Packages

- `MDAnalysis`