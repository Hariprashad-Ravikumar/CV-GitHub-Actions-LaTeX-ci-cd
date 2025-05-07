# Automated LaTeX CV 📄✨

This repository contains the LaTeX source files for my CV and utilizes a GitHub Actions workflow to automatically compile the LaTeX document into a PDF whenever changes are pushed. The compiled CV (`CV_HARI.pdf`) is automatically deployed and updated to my [GitHub Pages](https://hariprashad-ravikumar.github.io/cv/CV_HARI.pdf).

---

## 🚀 Workflow Overview

### Step-by-Step Automation:

1. **LaTeX Source Updates**:
   - Edit and maintain CV content directly via `main.tex`.
   - Push changes to GitHub repository.

2. **GitHub Actions Trigger**:
   - Automatically triggered upon pushing `.tex`, `.bib`, `.sty` files, or workflow updates.

3. **Automated PDF Compilation**:
   - Uses `latexmk` on Ubuntu to reliably compile LaTeX sources.

4. **Automatic PDF Deployment**:
   - Pushes the compiled PDF (`CV_HARI.pdf`) directly into the `cv` directory of my GitHub Pages repository ([hariprashad-ravikumar.github.io](https://hariprashad-ravikumar.github.io/cv/CV_HARI.pdf)).

5. **Continuous Deployment**:
   - Always ensures the latest version of the CV is immediately available online.

---

## 🔧 Technology Stack:

- **LaTeX** (via `latexmk`)
- **GitHub Actions** for CI/CD automation
- **GitHub Pages** for static site hosting
- **Bash scripting** for deployment automation

---


