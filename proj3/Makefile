PROJ=proj3
CONVERTED=-eps-converted-to
PACKNAME=xcernoj00

$(PROJ).pdf: $(PROJ).tex
	pdflatex $(PROJ).tex
	pdflatex $(PROJ).tex

pack:
	rm -f $(PACKNAME).zip
	zip $(PACKNAME).zip \
		proj3.tex \
		Makefile \
		*.eps \
		*.sty \

clean:
	rm -f $(PROJ).aux $(PROJ).dvi $(PROJ).log $(PROJ).ps $(PROJ).out

clean-all: clean
	rm -f $(PROJ).pdf $(PROJ).fdb_latexmk $(PROJ).fls etiopan$(CONVERTED).pdf oniisan$(CONVERTED).pdf oniisan2$(CONVERTED).pdf
