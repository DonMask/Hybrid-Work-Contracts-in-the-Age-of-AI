# ContractsAI Project

This repository contains the source files for the ContractsAI project, a LaTeX document compiled using Overleaf. The document is structured to include references directly within the main LaTeX file.

## Project Structure

The repository includes the following files:

- **LICENSE**: The license file outlining the terms of use for this project.
- **ContractsAi.pdf**: The compiled PDF output of the LaTeX document.
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
   - Ensure all dependencies (e.g., packages specified in `main.tex`) are supported by Overleaf. Common packages like `bibentry`, `natbib`, or `biblatex` (used for references) are typically pre-installed.

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
   - Ensure BibTeX is included for processing references.

2. **Set Up Files**:
   - Clone or download this repository to your local machine.
   - Ensure `main.tex` and any referenced files (e.g., `.bib` files, if used) are in the same directory.

3. **Compile the Document**:
   - Open a terminal or command prompt in the project directory.
   - Run the following commands to compile with references:
     ```bash
     pdflatex main.tex
     bibtex main  # Only if a separate .bib file is used
     pdflatex main.tex
     pdflatex main.tex
     ```
     Note: If references are embedded directly in `main.tex` (e.g., using a manual bibliography), the `bibtex` step may not be needed.

4. **View the Output**:
   - The compiled `main.pdf` will be generated in the project directory.
   - Open it with a PDF viewer to verify the output.

## References

The references for the document are included directly within `main.tex`. This may involve:
- A manual bibliography defined using `\begin{thebibliography}...\end{thebibliography}`.
- Alternatively, references may use a LaTeX package like `bibentry` or `natbib` with inline entries.
- If a separate `.bib` file is used (not listed in the provided structure), ensure it is included in the project directory and properly referenced in `main.tex`.

## Notes

- Ensure all LaTeX packages specified in `main.tex` are available in your compilation environment. Overleaf typically supports most standard packages.
- If you encounter compilation errors, check for missing packages or syntax errors in `main.tex`.
- The provided `ContractsAi.pdf` is a pre-compiled version of the document for reference.

## License

This project is licensed under the terms specified in the `LICENSE` file.

## Contact

For questions or issues with compilation, feel free to open an issue in this repository or contact the project maintainer.
