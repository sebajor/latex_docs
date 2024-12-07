DOCNAME ?= sample-doc

quick:
	pdflatex $(DOCNAME).tex

all:
	pdflatex $(DOCNAME).tex
	bibtex $(DOCNAME).aux
	pdflatex $(DOCNAME).tex
	pdflatex $(DOCNAME).tex


clean:
	rm -rf *.blg *.aux *.toc *.log $(DOCNAME).pdf *.bbl *.lof *.lot *.out
