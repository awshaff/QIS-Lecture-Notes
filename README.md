# Quantum Information Science: Comprehensive Lecture Notes

A comprehensive academic textbook covering quantum information science from foundational principles to cutting-edge applications.

## Overview

This repository contains the LaTeX source for "Quantum Information Science: Comprehensive Lecture Notes" by Ruang Kuantum. The book provides a thorough treatment of quantum information theory, quantum computing, quantum communication, and related fields, designed for graduate students and researchers.

## Table of Contents

The book is organized into 13 comprehensive chapters:

1. **From Classical to Quantum Information** - Information theory fundamentals and quantum primitives
2. **Mathematical Framework** - Linear algebra, Hilbert spaces, and quantum operations  
3. **Quantum Mechanics and Measurement** - Dynamics, measurement theory, and open systems
4. **Entanglement and Quantum Correlations** - Entanglement theory and Bell inequalities
5. **Quantum Circuits and Gates** - Circuit model and universal gate sets
6. **Quantum Algorithms - Core Primitives** - QFT, phase estimation, Grover's algorithm
7. **NISQ Algorithms and Variational Methods** - VQE, QAOA, and error mitigation
8. **Quantum Communication Protocols** - Teleportation, superdense coding, channel capacity
9. **Quantum Key Distribution Systems** - QKD protocols and security analysis
10. **Quantum Sensing and Metrology** - Parameter estimation and interferometry
11. **Quantum Error Correction** - Stabilizer codes and fault tolerance
12. **Quantum Hardware Platforms** - Physical implementations and control systems
13. **Quantum Networks and Internet** - Network architecture and protocols

## Building the Document

### Prerequisites
- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- PDF viewer for output

### Compilation
To compile the PDF:

```bash
pdflatex lecture-note.tex
```

For complete compilation with cross-references and table of contents:

```bash
pdflatex lecture-note.tex
pdflatex lecture-note.tex
```

### Output
The compiled PDF will be generated as `lecture-note.pdf`.

## Repository Structure

```
├── lecture-note.tex        # Main LaTeX source file
├── lecture-note.pdf        # Compiled PDF output
├── README.md              # This file
├── CLAUDE.md              # Development guidance
└── .gitignore             # Git ignore configuration
```

## LaTeX Configuration

The document uses:
- Document class: `book` (12pt, A4 paper)
- Mathematical packages: `amsmath`, `amsfonts`, `amssymb`
- Page layout: `geometry` with 1-inch margins
- Hyperlinks: `hyperref` with colored links
- Custom formatting: `tocloft`, `titlesec`

## Contributing

This is an academic book project. The content is structured with extensive chapter and section hierarchies, currently containing detailed outlines ready for content development.

## License

Academic use only. Please contact the author for permissions regarding distribution or commercial use.

## Author

**Ruang Kuantum**

*Quantum Information Science: Comprehensive Lecture Notes*
