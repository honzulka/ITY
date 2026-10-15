all: proj4.pdf

proj4.pdf: proj4.tex proj4.bib
	pdflatex proj4.tex
	bibtex proj4
	pdflatex proj4.tex
	pdflatex proj4.tex

clean:
	rm -f *.aux *.bbl *.blg *.log *.out *.toc
