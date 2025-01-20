DOCNAME ?= main
#the doc name use to be reporte.. but I got a lot of error when downloading it

quick:
	pdflatex $(DOCNAME).tex

all:
	pdflatex $(DOCNAME).tex
	echo "BIBTEX RUN"
	bibtex $(DOCNAME).aux
	echo "PDF LATEX RUN"
	pdflatex $(DOCNAME).tex
	pdflatex $(DOCNAME).tex


clean:
	rm -rf *.blg *.aux *.toc *.log $(DOCNAME).pdf *.bbl *.lof *.lot *.out *.run.xml
