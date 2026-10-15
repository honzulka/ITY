PROJ = proj2
suff = dvi log blg bbl toc aux tmp out vrb

$(PROJ).pdf: $(PROJ).tex
	pdflatex $(PROJ)
	pdflatex $(PROJ)

clean:
	$(foreach s, $(suff), rm -f $(PROJ).$(s))

clean-all: clean
	rm -f $(PROJ).pdf
