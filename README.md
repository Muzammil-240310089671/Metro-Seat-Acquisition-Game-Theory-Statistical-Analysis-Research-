# Metro Seat Acquisition: Game Theory & Statistical Analysis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

## Abstract

This repository contains a comprehensive game-theoretic and behavioral model for optimizing metro seat acquisition during peak hours. Using synthetic data calibrated to Chennai Metro Rail (CMRL) statistics, we compute Nash equilibrium strategies and provide evidence-based recommendations for commuters and metro operators.

**Key Findings:**
"Imagine you're at Chennai Metro during rush hour. Hundreds of people competing for a handful of seats. What's your strategy?

We analyzed this scientifically, and here's what we found:

One: Most people rush to the FRONT of the train. Big mistake. The BACK carriages - cars 5 and 6 - have way more empty seats because everyone ignores them. Simple fix: walk to the back of the platform.

Two: Does pushing and shoving help? We tested this. Answer: NO. Aggressive passengers get into conflicts, waste energy, and end up with the SAME seat success rate as calm passengers. So relax - it doesn't help.

Three: Timing is everything. During 60% crowding, you have a 1-in-4 chance of sitting. At 90% crowding? Only 1-in-10. If you can shift your travel time by just 30 minutes, your experience improves dramatically.

Four: Special warning for Chennai Central evening commuters. The data shows waiting 15 minutes for the next train actually gets you there more comfortably than boarding into the first overcrowded train.

And here's the smart trick: Watch for passengers picking up their bags or standing up. They're about to leave. Position yourself nearby (politely), and you might catch their seat when they exit.

Bottom line: Walk to the back, stay calm, and time it right. Science can help you win the metro seat game."

## Extended Finding: Platform Architecture Matters

Our model assumes single-platform access. However, most Chennai Metro stations have **dual entry points** (front and back), which changes the optimal strategy:

**Revised Recommendation:**
- Target **middle carriages (3-4)** at dual-entry stations
- These cars receive less passenger flow from both ends
- Validated by observing actual crowd distribution patterns

This demonstrates how **infrastructure design** interacts with **passenger behavior** to shape equilibrium strategies.



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








