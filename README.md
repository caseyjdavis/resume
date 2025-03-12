# My resume generated in Pandoc using Markdown
Takes the hassle out of formatting your resume by simple Markdown and version control!

## Requirements:
- pandoc
- weasyprint

## Installation

Install requirements, I was able to do this easily in Ubuntu with

```bash
sudo apt install pandoc weasyprint -y
```

Then clone this repository and build using pandoc

```bash
git clone https://github.com/caseyjdavis/resume.git

cd resume

pandoc resume.md -o resume.pdf --pdf-engine=weasyprint --css resume-css-stylesheet.css
```

## Finished product

Pandoc will export a finished resume.pdf file in the current folder