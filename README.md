# ContractsAI Project

This repository contains the source files for the ContractsAI project, a LaTeX document compiled using Overleaf. The document is structured to include references directly within the main LaTeX file.

## Project Structure

The repository includes the following files:

- **ContractsAi.pdf**: The compiled PDF output of the LaTeX document.
- **LICENSE**: The license file outlining the terms of use for this project.
- **README.md**: This file, providing an overview and instructions for the project.
- **main.tex**: The main LaTeX source file, containing the document content and references.

## Prerequisites

To compile and work with this project, you need:

- An **Overleaf** account (free or paid) to compile the LaTeX document online.
- Alternatively, a local LaTeX distribution (e.g., TeX Live, MiKTeX) with a LaTeX editor (e.g., TeXShop, VS Code with LaTeX Workshop) if compiling locally.
- Basic familiarity with LaTeX syntax for editing the document.

## Compilation Instructions

### Using Overleaf
1. **Upload the Project**:
   - Create a new project in Overleaf.
   - Upload the `main.tex` file (and any additional files referenced in `main.tex`, if applicable) to the Overleaf project.

2. **Compile the Document**:
   - Open `main.tex` in the Overleaf editor.
   - Click the **Compile** button (or "Recompile") to generate the PDF.
   - Overleaf automatically handles the compilation process, including processing references included in `main.tex` (e.g., using BibTeX or inline bibliography).

3. **View Output**:
   - The compiled PDF will appear in the Overleaf preview pane.
   - Download the PDF or compare it with the provided `ContractsAi.pdf` for reference.

### Local Compilation
If you prefer to compile the document locally:

1. **Install a LaTeX Distribution**:
   - Download and install a LaTeX distribution like TeX Live (Linux/Mac) or MiKTeX (Windows).

2. **Set Up Files**:
   - Clone or download this repository to your local machine.
   - Ensure `main.tex` is in the same directory.

3. **Compile the Document**:
   - Open a terminal or command prompt in the project directory.
   - Run the following commands to compile with references:
     ```bash
     pdflatex main.tex
     ```
     Note:  All references are included directly in the `main.tex` file to avoid external `.bib` dependencies.  
  This ensures smooth compilation and ease of use, especially in Overleaf environments.

4. **View the Output**:
   - The compiled `main.pdf` will be generated in the project directory.
   - Open it with a PDF viewer to verify the output.
```
@misc{berger2025transition,
  author       = {Teodor Berger},
  title        = {A Legal and Economic Transition Model for AI Integration in the Workforce},
  year         = {2025},
  doi          = {10.5281/zenodo.15475991},
  publisher    = {Zenodo},
  version      = {v1.0.1},
  url          = {https://doi.org/10.5281/zenodo.15475991}
}
```
## Notes

- Ensure all LaTeX packages specified in `main.tex` are available in your compilation environment. Overleaf typically supports most standard packages.
- If you encounter compilation errors, check for missing packages or syntax errors in `main.tex`.
- The provided `ContractsAi.pdf` is a pre-compiled version of the document for reference.

## License

This project is licensed under the terms specified in the `LICENSE` file.

## Contact

bergerteodor@googlemail.com

https://github.com/DonMask/Hybrid-Work-Contracts-in-the-Age-of-AI/tree/main
