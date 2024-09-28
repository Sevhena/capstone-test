# Makefile
# From https://danielkaes.wordpress.com/2009/03/14/compiling-latex-documents-using-makefiles/

PROJECT=DevelopmentPlan
TEX=latexmk
BUILDTEX=$(TEX) -pdf $(PROJECT).tex

all:
	$(BUILDTEX)

clean-all:
	rm -f *.log *.bak *.aux *.bbl *.blg *.idx *.ps *.eps *.pdf *.fdb_latexmk *.fls *.dvi *.toc *.synctex.gz *.out *~

clean:
	rm -f *.log *.bak *.aux *.bbl *.blg *.idx *.toc *.synctex.gz *.fdb_latexmk *.fls *.dvi *.out *~