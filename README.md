# 📄 Resume Collection

This repository contains my professional resumes, automatically compiled using GitHub Actions.

## 🚀 Available Resumes

### 📌 Fullstack Resume

[![Download PDF](https://img.shields.io/badge/Download-PDF-red?style=for-the-badge&logo=adobe-acrobat-reader)](https://github.com/NodeVigil/resume/releases/latest/download/fullstack-resume.pdf)
[![View Source](https://img.shields.io/badge/View-Source-blue?style=for-the-badge&logo=latex)](./fullstack/main.tex)

---

## 📊 Build Information

- **Latest Release:** [`v8`](https://github.com/NodeVigil/resume/releases/latest)
- **Last Updated:** December 30, 2025 at 04:25 UTC
- **Auto-compiled:** ✅ Yes, on every push to main

## 🛠️ Technical Details

### Structure
```
/
├── fullstack/          # Fullstack resume variant
├── common/         # Shared LaTeX components
└── README.md       # This file (auto-generated)
```

### Compilation
- **Engine:** LaTeX (latexmk with pdflatex)
- **CI/CD:** GitHub Actions
- **Distribution:** Releases are created automatically on every push

### How It Works
1. Push changes to `main` branch
2. GitHub Actions compiles all LaTeX files
3. PDFs are committed back to repository
4. A new release is created with downloadable PDFs
5. This README is automatically updated

## 📥 Download Options

### Latest Release (Recommended)
Download the most recent compiled versions from the [latest release](https://github.com/NodeVigil/resume/releases/latest).

### Direct from Repository
- [`fullstack-resume.pdf`](./fullstack/fullstack-resume.pdf)

### All Releases
Browse all previous versions in the [releases page](https://github.com/NodeVigil/resume/releases).

---

<div align="center">

**⭐ Star this repo if you find it useful!**

![Build Status](https://img.shields.io/github/actions/workflow/status/NodeVigil/resume/compile-resumes.yml?branch=main&style=flat-square)
![Latest Release](https://img.shields.io/github/v/release/NodeVigil/resume?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/NodeVigil/resume?style=flat-square)

</div>
