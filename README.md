# CV

[![LaTeX](https://img.shields.io/badge/Built%20with-LaTeX-008080.svg)](https://www.latex-project.org/)
[![Status](https://img.shields.io/badge/Status-Maintained-green.svg)]()

**"Career as Code."**

This repository hosts the source code (`.tex`) and compiled binaries (`.pdf`) of my professional resume. Maintained in version control because a career is an iterative process, not a static document.

## 📥 Downloads

| Version | Description | Use Case | Link |
| :--- | :--- | :--- | :--- |
| **Digital** | Clean UI with embedded clickable hyperlinks. | Email, LinkedIn, ATS Uploads. | **[Download Digital PDF](Bhushan_Ladgaonkar_Resume.pdf)** |
| **Print** | Full URLs explicitly written out. | Physical Interviews, Career Fairs. | **[Download Print PDF](Bhushan_Ladgaonkar_Resume_Print.pdf)** |

> *Note: The Print version exposes full URLs (e.g., `github.com/beeth73`) because paper doesn't support `onClick` events yet.*

## 🛠 Build Instructions
To compile from source (requires TeX Live / MacTeX):

```bash
# Compile Digital Version
pdflatex jobname=Digital_Resume main.tex

# Compile Print Version (toggles internal boolean for URL display)
pdflatex jobname=Print_Resume "\def\isprint{1} \input{main.tex}"

```

## 📄 Philosophy
*   **ATS Friendly:** Single column, standard fonts, machine-parsable.
*   **Versioned:** Every update is a commit. History is preserved.
*   **Minimalist:** Content over decoration. High signal-to-noise ratio.

---
*© 2025 Bhushan Ladgaonkar*
