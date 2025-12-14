![Build LaTeX document](https://github.com/sinan-online/dnd-latex-template-repo/actions/workflows/main.yml/badge.svg)
# 🐉 D&amp;D L<sup>A</sup>T<sub>E</sub>X Template

A template repo to create D&amp;D documents using L<sup>A</sup>T<sub>E</sub>X.

## 📖 Introduction

This template uses the excellent [DND 5e LaTeX Template](https://github.com/rpgtex/DND-5e-LaTeX-Template) L<sup>A</sup>T<sub>E</sub>X class created by the rpgtex team under the [MIT License](https://github.com/rpgtex/DND-5e-LaTeX-Template/blob/master/LICENSE). All credit for the L<sup>A</sup>T<sub>E</sub>X class goes to the original authors.

## 🚀 Quick Start

1. 📥 Clone the repo (Need Git knowledge for this, and Git installed. Git Desktop should do fine if you are starting.)
2. 💻 Open in VS Code, "open in container" when prompted. If in container, you can use a VS Code task to compile. Write in the file `tex/example.tex` or create your own file.
3. ☁️ You do not have to use VS Code. If you are on GitHub, when you "git push", it will compile and create a PDF file on the repo. Only change the env `BASENAME` from `example` in  `.github/workflows/main.yml` to whatever your file name is.
