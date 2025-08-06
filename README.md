# .NET Aspire – Study Notes + Tutorial 2025

[![PDF download](https://img.shields.io/badge/PDF-download-blue)](https://github.com/konradcinkusz/dotNET_Aspire_Summary_Tutorial/releases/latest/download/DotNetAspire_StudyNotes.pdf)
[![CI](https://github.com/konradcinkusz/dotNET_Aspire_Summary_Tutorial/actions/workflows/ci.yml/badge.svg)](https://github.com/konradcinkusz/dotNET_Aspire_Summary_Tutorial/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A **comprehensive LaTeX reference** to Microsoft’s cloud-native toolkit *“.NET Aspire”*.  
The document blends concise theory with a full walk-through that scaffolds a distributed
solution (API + worker + PostgreSQL + Redis) and shows how to orchestrate everything through **Aspire AppHost**.

---

## Features

* **End-to-end tutorial** – every command, snippet and migration covered.
* **Opinionated cheat-sheets** – design pillars, helper APIs, CLI flags.
* **Syntax-highlighted code** via *minted* (Pygments).
* **Single-click PDF** – generated automatically by GitHub Actions on each version tag.
* **Easy to extend** – drop a new section or image; the CI workflow does the rest.

---

## Quick start

```bash
git clone https://github.com/konradcinkusz/dotnet-aspire-notes.git
cd dotnet-aspire-notes
latexmk -pdf -shell-escape aspire-notes.tex          # or xelatex twice
