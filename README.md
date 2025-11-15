# Metro Seat Acquisition: Game Theory & Statistical Analysis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

## Abstract

This repository contains a comprehensive game-theoretic and behavioral model for optimizing metro seat acquisition during peak hours. Using synthetic data calibrated to Chennai Metro Rail (CMRL) statistics, we compute Nash equilibrium strategies and provide evidence-based recommendations for commuters and metro operators.

**Key Findings:**
- Optimal aggressiveness = 0.0 (universal passivity)
- Standing cost dominates payoff (~10 units per 10% crowding increase)
- Rear carriages (5-6) consistently optimal
- Chennai Central at 90% crowding: payoff -52.7 (wait recommended)

## Repository Contents

- **docs/**: Research reports (Markdown & LaTeX), figures
- **equations/**: Mathematical formulations (baseline + behavioral extensions)
- **data/**: Synthetic passenger dataset (3,600 records), Nash equilibrium strategies
- **src/**: Python implementation (payoff functions, Nash solver, simulation)
- **notebooks/**: Jupyter notebooks for data generation and analysis

## Quick Start

### For Researchers & Students

**View the Research:**

1. **Read the full report** (no installation needed):
   - Go to `docs/metro-research-final.md`
   - GitHub renders it automatically with formatting

2. **See the equations**:
   - Go to `equations/updated_equations_behavioral.md`
   - Contains all mathematical formulations

3. **View the results**:
   - Open `data/nash_equilibrium_strategies.csv` in Excel
   - See optimal strategies for all stations and crowding levels








