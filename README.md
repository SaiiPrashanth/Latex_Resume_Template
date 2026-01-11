# LaTeX Resume Template

A clean, professional, and easy-to-use **LaTeX** resume template designed for clarity and readability.

## Features

- **Custom Class**: Uses a dedicated `resume.cls` file to abstract formatting logic.
- **Structured Sections**: Pre-defined environments for:
  - Objective
  - Education
  - Skills
  - Experience
  - Projects
- **Clean Layout**: optimized margins and font spacing for professional presentation.

## Usage

1. **Prerequisites**: Ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX) or use an online editor like Overleaf.
2. **Edit**: Open `Template/resume.tex` and replace the placeholder content with your own information.
3. **Build**: Compile the `.tex` file using `pdflatex`.

## File Structure

- `Template/resume.tex`: The main content file where you add your data.
- `Template/resume.cls`: The styling class file. Do not edit unless you want to change the global layout.
- `Template/resume.pdf`: An example output of the template.

## Script Reference

### `Template/resume.cls`
The backend styling class.
- Defines the `resume` document class.
- Configures page margins using the `geometry` package.
- Defines custom commands like `\name`, `\address`, and the `rSection` environment for consistent formatting.

### `Template/resume.tex`
The frontend content file.
- **Structure**:
  - `\documentclass{resume}`: Imports the custom class.
  - `Header`: Sets name and contact info.
  - `\begin{rSection}{...}`: Creates clearly defined sections for Objective, Education, Skills, etc.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
Copyright (c) 2026 ARGUS