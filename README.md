# 📄 Nithin E - Data Science Resume

This repository contains the source code for my professional Data Scientist resume, written in **LaTeX**.

By hosting the source code on GitHub, I can easily version control my resume, track changes over time, and update my skills and experiences from any machine.

---

## 🛠️ Prerequisites

To compile the LaTeX file into a PDF on your local machine, you will need a LaTeX distribution installed:

- **Windows:** [MiKTeX](https://miktex.org/) or [TeX Live](https://tug.org/texlive/)
- **Linux:** `texlive-full` (e.g., `sudo apt install texlive-full` for Ubuntu/Debian or Arch)
- **macOS:** [MacTeX](https://tug.org/mactex/)

The resume relies on standard LaTeX packages such as `geometry`, `titlesec`, `hyperref`, and `mathpazo` (for the elegant Palatino font). Modern LaTeX distributions (like MiKTeX) should automatically download any missing packages during compilation.

---

## 🚀 How to Compile

**For Windows Users:**
The easiest way to compile the resume is to simply double-click the `compile.bat` file in your File Explorer. This script automatically runs the compiler and keeps the terminal open so you can check for any errors.

**Using the Terminal (Mac/Linux/Windows):**
You can also generate the PDF manually by running the following command in your terminal from the root directory of this repository:

```bash
pdflatex DA_Resume.tex
```

This will generate (or overwrite) the `DA_Resume.pdf` file in the same directory.

*(Note: If you don't want to install LaTeX locally, you can easily copy and paste the `DA_Resume.tex` code into an online editor like [Overleaf](https://www.overleaf.com/) to edit and compile it directly in your browser.)*

---

## 📝 Editing the Resume

1. Open `DA_Resume.tex` in your favorite text editor (VS Code with the LaTeX Workshop extension is highly recommended).
2. The document is divided into clear, highly readable sections (Header, Summary, Technical Skills, Projects, Certifications, Education). 
3. Locate the section you want to update (e.g., adding a new tool to Technical Skills), edit the text, and save the file.
4. Run `pdflatex DA_Resume.tex` to instantly see your changes in the generated PDF.
