# Bachelor Thesis Template (Typst)

A unofficial Typst template for Bachelor thesis at University of Applied Sciences Upper Austria.

## Prerequisites
- [VSCode](https://code.visualstudio.com/) with [Tinymist](https://marketplace.visualstudio.com/items?itemName=myriad-dreamin.tinymist) extension

## Quick Start

1. **Clone this repository:**
   ```bash
   git clone https://github.com/MichaelBogensberger/Hagenberg-Thesis-Typst.git
   cd Hagenberg-Thesis-Typst
   ```

2. **Configure your thesis data:**
   Edit `metadata.typ` with your personal information:
   ```typ
   #let titleEnglish = "Your Thesis Title"
   #let degree = "Bachelor" // or "Master"
   #let program = "Your Study Program"
   #let supervisor = "Your Supervisor Name"
   #let author = "Your Name"
   #let submissionDate = datetime(day: 1, month: 6, year: 2024)
   ```

3. **Compile your thesis:**
   - Open `thesis.typ` in VSCode with Tinymist extension
   - Click on preview or export to pdf.

## Usage

1. **Edit your content** in the `content/` folder - each chapter has its own file
2. **Add figures** to the `figures/` folder and reference them in your content
3. **Add bibliography entries** to `thesis.yml` in YAML format
4. **Customize the template** by modifying files in the `layout/` folder if needed

## Features

- ✅ Professional layout compliant with university standards
- ✅ Automatic table of contents, figures, and tables
- ✅ Bibliography management with YAML
- ✅ German and English abstracts
- ✅ Glossary and transparency declaration for AI tools
- ✅ Modular chapter structure

## Compilation

**With VSCode + Tinymist:**
- The extension provides live preview and auto-compilation
- Export to PDF via command palette

**Command line:**
```bash
typst compile thesis.typ
```

## License

This template is provided as-is for academic use. Modify as needed for your institution's requirements.
