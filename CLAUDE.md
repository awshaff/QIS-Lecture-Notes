# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a LaTeX-based academic book project for "Quantum Information Science: Comprehensive Lecture Notes" by Ruang Kuantum. The repository contains a single comprehensive LaTeX document that covers quantum information science from fundamentals to advanced topics.

## File Structure

- `lecture-note.tex` - Main LaTeX source file containing the complete book content
- `lecture-note.pdf` - Compiled PDF output 
- `lecture-note.synctex.gz` - SyncTeX file for editor integration
- `README.md` - Basic project description
- `.gitignore` - Comprehensive LaTeX gitignore configuration

## Build Commands

### Compile PDF
```bash
pdflatex lecture-note.tex
```

For complete compilation with cross-references and table of contents:
```bash
pdflatex lecture-note.tex
pdflatex lecture-note.tex
```

## Document Architecture

The book is structured as a comprehensive academic text with 12 chapters covering:

1. **Classical to Quantum Information** - Information theory fundamentals and quantum primitives
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

## LaTeX Configuration

The document uses the `book` document class with these key packages:
- `amsmath`, `amsfonts`, `amssymb` for mathematical typesetting
- `hyperref` for internal linking and PDF metadata
- `geometry` with 1-inch margins
- `tocloft` and `titlesec` for custom formatting

## Working with This Repository

- All content is contained in the single `lecture-note.tex` file
- The document is structured with extensive chapter and section hierarchy
- Currently contains chapter outlines and section headings without full content
- Cross-references and internal linking are configured via hyperref
- SyncTeX integration enables editor-PDF synchronization