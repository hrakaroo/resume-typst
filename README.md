# Resume

This repository contains a professional resume template in [Typst](https://typst.app/) - a modern markup-based typesetting system.

This project also uses GitHub workflows to automatically build the resume.  See
[releases](https://github.com/hrakaroo/resume-typst/releases) to view the latest version of the example resume.

## Installation (Mac)

Install Typst using Homebrew:

```bash
brew install typst
```

## Update the configuration

Update the configuration.xml with your data.

## Building the Resume

Compile the resume to PDF:

```bash
typst compile resume.typ
```

This will generate `resume.pdf` in the current directory.

## Structure

- `resume.typ` - Main resume template
- `configuration.yaml` - Resume content and data
- `icons/` - SVG icons for contact information

## Icons

Icons can be found at https://fonts.google.com/icons
