-------------------------------------------------------------------------
uefcsthesis --- LaTeX style for BSc and MSc theses at UEF SoC
E-mail: pauli.miettinen@uef.fi
Licence: LaTeX Project Public License v1.3c or later
See https://www.latex-project.org/lppl.txt
-------------------------------------------------------------------------

Style uefcsthesis.cls is the style for UEF's School of Computing's BSc
and MSc these done with [Lua|Xe]LaTeX. The style supports MSc theses done under the
IMLEX MSc program with class option "imlex". The style comes in two different
packages:
  o uefcsthesis.[zip|tar.bz] - mandatory style files and a number of example
                               files
  o uefcsthesis-doc.zip - style file and its documentation and the source
                          files for the documentation

It's best to start writing one's own thesis by editing one of the minimal
example files in uefcsthesis-package. For IMLEX students, the recommended
file is the minima_imlex.tex. Further examples can be found in the
modern.tex and classic.tex files in the documentation package. That package
also contains the file sample_contents/body_en.txt, where one can see how
certain common structures in theses are done.

The documentation package contains an example and short user's guide
in the file sample.pdf; the in-depth user's guide of the style is in the file
uefcsthesis.pdf.

The original source codes for the class can be loaded from a git repository at
the cs.uef.fi server's GitLab with command
git clone git@cs.uef.fi:pauli/uefcsthesis.git
The repository can also be accessed via browser at
http://cs.uef.fi:8392/pauli/uefcsthesis.git
This requires user account at the server. The repository is read-only. To
generate the style file and other files, issue
make
and to generate the distribution packages, issue
make package
