# Contributing to PICKit Clone

First off, thank you for considering contributing to the PICKit Clone project! It's people like you that make the open-source community such an amazing place to learn, inspire, and create.

## 📍 The Development Workflow

Because this is a hardware project, we have a specific workflow to prevent conflicts and ensure stability.

1. Branching Strategy

main: This branch is for stable releases only. Do not commit directly to main.

designing: This is the active development branch for hardware. Please submit all Pull Requests (PRs) to this branch.

firmware: This is the active development branch for firmware. Please submit all Pull Requests (PRs) to this branch.

2. Creating a Pull Request

Fork the project.

Create your Feature Branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the Branch (git push origin feature/AmazingFeature).

Open a Pull Request targeting the designing branch of this repository.

## 🛠️ Hardware Contributions (Schematics & PCB)

Collaborating on binary hardware files (like .kicad_pcb or .PcbDoc) is difficult because Git cannot show "diffs" for them easily. To make reviewing your work easier, please follow these rules:

Small Changes: Try to keep hardware changes small and focused. Don't reroute the whole board and change the schematic in one commit.

Screenshots/PDFs: If you modify the Schematic or PCB, please include a screenshot or a PDF export in your Pull Request description. This allows us to see what changed without downloading the files and opening the CAD software.

Design Rule Check (DRC): Before submitting, ensure your design passes DRC with zero errors.

## 💻 Firmware Contributions

Coding Style: Please attempt to match the existing coding style (indentation, variable naming) found in the project.

Comments: Comment your code! Especially for timing-critical ICSP logic, explain why you are adding a delay or toggling a pin.

## 🐛 Reporting Bugs

If you find a bug in the hardware design or firmware, please create an Issue using the GitHub Issue tracker. Describe the problem in detail and, if possible, include steps to reproduce it.

## 💬 Code of Conduct

Please note that this project is intended to be a welcoming environment. We expect all contributors to be respectful and constructive in their communication.
