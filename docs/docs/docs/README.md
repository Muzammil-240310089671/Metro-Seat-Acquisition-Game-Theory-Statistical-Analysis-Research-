# Documentation

This folder contains the complete research documentation for the metro seat acquisition project.

## Files

### Research Reports

- **`metro-research.tex`** - LaTeX source file for publication-ready PDF
  - Contains all mathematical formulas properly formatted
  - Includes complete methodology, results, and recommendations
  - Ready for academic submission

- **`metro-research-final.md`** - Comprehensive research report in Markdown format
  - 20+ pages of detailed analysis
  - Readable in GitHub without compilation
  - Contains same content as LaTeX version

### Figures

- **`figures/`** - Directory containing all visualizations
  - `payoff-analysis.png` - Multi-panel payoff landscape charts
  - Additional charts as generated

## Building the PDF Report

### Method 1: Using Overleaf (Recommended - Easiest)

1. Go to [Overleaf.com](https://www.overleaf.com)
2. Create a free account (if you don't have one)
3. Click "New Project" → "Upload Project"
4. Upload `metro-research.tex`
5. Click "Recompile" button
6. Download the compiled PDF

**Advantages:**
- No local LaTeX installation needed
- Automatic error checking
- Cloud-based collaboration

### Method 2: Using Local LaTeX Installation

**Requirements:**
- LaTeX distribution installed:
  - **Windows:** [MikTeX](https://miktex.org/download) or [TeX Live](https://www.tug.org/texlive/)
  - **macOS:** [MacTeX](https://www.tug.org/mactex/)
  - **Linux:** `sudo apt-get install texlive-full`

**Compilation Steps:**

cd docs
pdflatex metro-research.tex
pdflatex metro-research.tex



Run twice for table of contents.

### Method 3: Online LaTeX Compiler

1. Go to [LaTeX Base](https://latexbase.com/)
2. Copy content of `metro-research.tex`
3. Paste into editor
4. Click "Compile" or "Download PDF"

## Document Structure

### LaTeX Document (`metro-research.tex`)

**Sections:**
1. Executive Summary
2. Game-Theoretic Framework
3. Payoff Function Formulation
4. Station-Specific Parameters
5. Nash Equilibrium Methodology
6. Dataset Description (3,600 passengers)
7. Results & Solutions
8. Sensitivity Analysis
9. Recommendations for Commuters
10. Policy Recommendations for CMRL
11. Conclusion

**Mathematical Content:**
- Master payoff equation
- Sigmoid seat acquisition probability
- Conflict, standing, and injury costs
- Nash equilibrium conditions
- Departure prediction model
- Level-k reasoning equations

## Viewing the Markdown Report

**On GitHub:**
- Navigate to `metro-research-final.md`
- GitHub automatically renders with formatting

**Locally:**
- VS Code: Ctrl+Shift+V for preview
- Or use Typora, Mark Text
- Convert to PDF: `pandoc metro-research-final.md -o output.pdf`

## Troubleshooting

### LaTeX Compilation Errors

**Missing packages:**
- Overleaf: Automatically installs
- Local: Run `tlmgr install [package-name]`

**Table of contents not updating:**
- Run pdflatex twice

**PDF not generating:**
1. Check installation: `pdflatex --version`
2. Try Overleaf instead
3. Use Markdown version (no compilation needed)

## Questions?

For questions about methodology or documentation:
- Open an issue on GitHub
- Contact: mohamedmuzammilak@gmail.com

---

**Last Updated:** November 15, 2025
