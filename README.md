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


## Overview

The main XeLaTeX source file is `resume.tex`; the compiled document is `resume.pdf`.

Instructions for compiling the document (TeX &rarr;(XeLaTeX)&rarr; PDF):

- **Method 1:** Use `latexmk` for fully automated document generation:
	- `latexmk -xelatex "CV.tex"`
	(add the `-pvc` switch to automatically recompile on changes)

- **Method 2:** Use `XeLaTeX` directly:
	- `xelatex "CV.tex"`
	(run multiple times to resolve cross-references if needed)
