# Metro Seat Acquisition: Game Theory & Statistical Analysis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

## Abstract

This repository contains a comprehensive game-theoretic and behavioral model for optimizing metro seat acquisition during peak hours. Using synthetic data calibrated to Chennai Metro Rail (CMRL) statistics, we compute Nash equilibrium strategies and provide evidence-based recommendations for commuters and metro operators.

## Key Findings

We analyzed 3,600 passenger journeys to find the best metro seat strategy. Since Chennai Metro stations have entrances at both ends, passengers cluster near entry points, making middle carriages less crowded.

What Works:
We analyzed 3,600 passenger journeys to find the best metro seat strategy. Since Chennai Metro stations have entrances at both ends, passengers cluster near entry points, making middle carriages less crowded.

**What Works:**
-  **Stand at platform center** - Board middle carriages (3-4) which are least occupied
-  **Stay calm** - Rushing doesn't improve your seat chances
-  **Avoid extreme peak** - 90% crowding = only 10% seat success rate
-  **Chennai Central evening** - Wait 6 minutes for next train instead
-  **Watch for departure cues** - People picking up bags are about to leave

**Bottom line:** Position yourself strategically, board calmly, and time your travel right. These simple changes can save you 5+ hours of standing per month.


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








