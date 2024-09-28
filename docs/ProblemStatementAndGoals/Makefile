# Makefile
# From https://danielkaes.wordpress.com/2009/03/14/compiling-latex-documents-using-makefiles/

PROJECT=ProblemStatement
TEX=latexmk
# BIBTEX=bibtex
BUILDTEX=$(TEX) $(PROJECT).tex

all:
	$(BUILDTEX)
#	$(BIBTEX) $(PROJECT)
#	$(BUILDTEX)
#	$(BUILDTEX)

clean-all:
	rm -f *.dvi *.log *.bak *.aux *.bbl *.blg *.idx *.ps *.eps *.pdf *.fdb_latexmk *.fls *.toc *.synctex.gz *.out *~

clean:
	rm -f *.dvi *.log *.bak *.aux *.bbl *.blg *.idx *.toc *.synctex.gz *.fdb_latexmk *.fls *.out *~