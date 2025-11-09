# Resume

Professional resume generated from LaTeX.

## Quick Start with Overleaf

1. Go to [Overleaf](https://www.overleaf.com/)
2. Create a free account (or login)
3. Click "New Project" → "Blank Project"
4. Delete the default content
5. Copy the entire content of `resume.tex` and paste it
6. Click "Recompile" to generate the PDF
7. Download the PDF from the download button

## Required Packages

The resume uses these LaTeX packages (all included in Overleaf):
- `inter` font (modern, professional sans-serif)
- `fontawesome5` (for icons)
- `hyperref` (for clickable links)
- `enumitem`, `titlesec` (for formatting)

## Local Compilation

If you want to compile locally:

```bash
# Install LaTeX on Arch Linux
sudo pacman -S texlive-basic texlive-latexextra texlive-fontsrecommended

# Compile
cd ~/code/nivekithan/resume
pdflatex resume.tex

# Output: resume.pdf
```

## Customization Tips

1. **Change Colors**: Search for `\color{black}` and replace with other colors like `\color{blue}` or define custom colors
2. **Adjust Margins**: Modify the `\addtolength` commands at the top
3. **Font Size**: Change `11pt` to `10pt` or `12pt` in `\documentclass`
4. **Add Education**: Uncomment the Education section at the bottom and fill in details
5. **Remove Sections**: Comment out or delete entire sections you don't need

## Structure

- **Heading**: Name and contact information
- **Summary**: Brief professional summary
- **Work Experience**: EPYC position with project details
- **Featured Projects**: Technical side projects
- **Live Production Projects**: Deployed applications
- **Technical Skills**: Technologies and tools
- **Education**: (Commented out - add if needed)

## Tips for ATS (Applicant Tracking Systems)

The resume is designed to be ATS-friendly:
- Uses standard section names
- No complex tables or graphics
- Clean, simple formatting
- Keywords from job descriptions should be naturally included

## PDF Output

After compilation, the PDF will be:
- **Format**: US Letter (8.5" x 11")
- **Font**: Inter (clean, modern sans-serif)
- **Style**: Professional, single-column layout
- **Length**: ~2 pages (adjust by removing projects if needed)
