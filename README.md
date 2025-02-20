# MaterialsCrow

## Overview
WIP: MaterialsCrow is an AI-driven framework for **automated materials simulations**, integrating **pymatgen, ASE, and DFT/MD engines**. It enables users to setup and run simulations via natural language prompts. The work is motivated from MDCrow repository by Andrew White's group. 

## Features
- Structure generation and manipulation (pymatgen, ASE)
- Automated DFT and MD input file creation
- Job submission to clusters (SLURM, PBS)
- Post-processing and visualization tools
- LLM-assisted workflow automation

## Installation
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/MaterialsCrow.git
cd MaterialsCrow
pip install -e .
