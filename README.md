# LaTeX Thesis Template - Università del Piemonte Orientale

This LateX template is designed to be modern and clean. The code is meticulously organized and fully customizable, to help you create a professional-looking thesis compliant with the official guidelines. The document structure is ready for a scientific research thesis but can be modified to meet your specific needs.

This document is not an official template. It's maintained by students for students as an open-source project and it's not affiliated to UPO in any way. The logos distributed with this project are intended for internal or authorized use only. The end user is responsible for any illegal use of this content.

<img width="1885" height="1322" alt="TemplatePreview" src="https://github.com/user-attachments/assets/339fae0b-52b4-457a-9427-b2393f3b9bb3" />

---

## How to use this template

### Option 1: Using Overleaf
1. Download this project as `.zip` (on the main page of this GitHub repo, click on **Code** -> **Download ZIP** in the top-right of the screen).
2. Open [Overleaf](https://www.overleaf.com) and login.
3. Click **New Project** -> **Upload Project** and select the `.zip` file you just downloaded.
4. **IMPORTANT:** In Overleaf, open the **Menu** and change your **Compiler** from *pdfLaTeX* to **LuaLaTeX**. Without this setting, the document might not compile or may differ from the expected result.

### Option 2: Local usage inside your editor (VS Code, TeXworks, Texmaker)
Install an up-to-date LaTeX distribution (TeX Live 2025+, MacTeX or MiKTeX) and follow your standard compilation workflow using the **LuaLaTeX** engine (`latexmk` is highly recommended for automatic management of bibliography and cross-references).

**IMPORTANT NOTE ON FONTS:** This document relies on system fonts (*Times New Roman* and *Fira Sans*). While Times New Roman is usually pre-installed on Windows and macOS, Fira Sans might not be. If a font is missing on your system, the compiler will automatically fall back to default fonts (like *Latin Modern*). You can change the fonts in `Config.tex` or install the required fonts.

---

## Project Structure

The code is organized in a modular way:
* `Main.tex`: It's the main file of the document. This will be your compilation target.
* `Config.tex`: Contains all the boilerplate code to include packages and set up the features of this template. You can modify parts of it to customize the graphical appearance, but do so with caution to avoid breaking the layout!
* `chapters/`: This folder contains all your chapters (ex. `01-Introduzione.tex`). You will write your content here, keeping it separate from the style configuration.
* `images/`: This is the root folder where you can place all your images and other external assets. Feel free to organize it with subfolders.
* `bibliography.bib`: This file will contain all your references in BibTeX format.

---
