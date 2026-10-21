# Design of Enterprise IoT

Coursework and supporting materials for the **Design of Enterprise IoT** unit at Jinling Institute of Technology.

The current assignment project is the **Smart Turtle Breeding System (STBS)**, an enterprise IoT solution for aquaculture. It combines water-quality sensing, automated feeding and temperature control, bounded partial water changes, edge processing, cloud monitoring, and operator alerts.

## Repository structure

- `assignments/` — assignment source files and working assets.
- `assignments/assignment-A1a/` — LaTeX source, figures, and the compiled submission for Assignment 1a.
- `assignments/assignment-A1b/` — LaTeX source, APA references, Excel-exported tables, figures, and the compiled submission for Assignment 1b.
- `JIT G24 Design of Enterprise IoT/` — course slides, tutorial handouts, assessment briefs, templates, and personal assessment files.

## Build Assignment 1a

The report uses XeLaTeX and `biblatex`. From `assignments/assignment-A1a`, run:

```powershell
latexmk -xelatex main.tex
```

The compiled report is written to `main.pdf`. Temporary LaTeX build files are excluded from version control.

## Build Assignment 1b

The Assignment 1b report is in `assignments/assignment-A1b`. Its device, network, and edge/cloud tables are exported from `assignments/assA1.xlsx` and embedded as PDFs rather than recreated in LaTeX. From that directory, run:

```powershell
latexmk -xelatex main.tex
```

The compiled report is written to `main.pdf`.

## Project status

- Assignment 1a: Smart Turtle Breeding System use case, solution overview, and value proposition.
- Assignment 1b: IoT device profiles, connectivity, edge/fog/cloud design, architecture diagram, and implementation references.

## Access

This repository contains coursework and course-provided materials and is intended for private academic collaboration only.
