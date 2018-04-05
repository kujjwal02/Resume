# Resume

My resume or curriculum vitae (CV), in XeLaTeX.

**Fork of:**<br>
https://github.com/zachscrivena/simple-resume-cv

**Website:**<br>
https://github.com/kujjwal02/

**Author:**<br>
Ujjwal Kumar (kujjwal02@gmail.com)

**Compiled document:**<br>
[Resume.pdf](https://raw.githubusercontent.com/kujjwal02/Resume/master/resume.pdf)


## Main Features

- Simple template that can be further customized or extended.
- Template document contains numerous examples.
- Direct support for TrueType (TTF) and OpenType (OTF) fonts.
- Direct support for multilingual Unicode characters, with the appropriate fonts.
- Hyperlinks can be included in generated PDF.

## Overview

The main XeLaTeX source file is `resume.tex`; the compiled document is `resume.pdf`.

Instructions for compiling the document (TeX &rarr;(XeLaTeX)&rarr; PDF):

- **Method 1:** Use `latexmk` for fully automated document generation:
	- `latexmk -xelatex "CV.tex"`
	(add the `-pvc` switch to automatically recompile on changes)

- **Method 2:** Use `XeLaTeX` directly:
	- `xelatex "CV.tex"`
	(run multiple times to resolve cross-references if needed)
