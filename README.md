# Quantum Information Science: Comprehensive Lecture Notes

A comprehensive academic textbook covering quantum information science from foundational principles to cutting-edge applications.

## Overview

This repository contains the LaTeX source for "Quantum Information Science: Comprehensive Lecture Notes" by Ruang Kuantum. The book provides a thorough treatment of quantum information theory, quantum computing, quantum communication, and related fields, designed for graduate students and researchers.

## Table of Contents

The book is organized into 12 comprehensive chapters:

1. **From Classical to Quantum Information** - Classical information fundamentals, qubits, superposition, entanglement, and basic quantum computation rules
2. **Essential Linear Algebra Toolkit** - Complex numbers, vectors, matrices, tensor products, and mathematical foundations for quantum computing
3. **Quantum Circuits and Single-Qubit Gates** - Circuit model, Pauli gates, Hadamard gate, phase gates, and Bloch sphere representation
4. **Multi-Qubit Gates and Universality** - CNOT, controlled gates, universal gate sets, and introductory algorithms (Deutsch-Jozsa)
5. **Quantum Algorithms I: Searching and Factoring** - Quantum Fourier Transform, phase estimation, Shor's algorithm, and Grover's search
6. **Quantum Communication and Information Theory** - Von Neumann entropy, quantum teleportation, superdense coding, and quantum key distribution (BB84, E91)
7. **Quantum Algorithms II: NISQ Algorithms and Hybrid Computation** - NISQ era, VQE, QAOA, and quantum machine learning
8. **Quantum Sensing and Metrology** - Classical vs quantum limits, NOON states, squeezed states, quantum magnetometry, and clock synchronization
9. **Open Systems and Decoherence** - System-environment interaction, density matrices, mixed states, and quantum control concepts
10. **Quantum Error Correction (QEC) Fundamentals** - Necessity of QEC, basic quantum codes, and introduction to stabilizer formalism
11. **Quantum Hardware Platforms** - Qubit quality metrics, major technologies (superconducting, trapped ion, photonic), and control systems
12. **Quantum Networking and Future** - Quantum networks, quantum repeaters, distributed quantum services, and the path to fault tolerance

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
