# Soubor:   proj1.tex
# Datum:    9.3.2026
# Autor:    Jan Černoch (xcernoj00)
# Projekt:  ITY proj 1

PROJ=proj1

$(PROJ).pdf: $(PROJ).tex
	latex $(PROJ).tex
	latex $(PROJ).tex
	dvips -t a4 $(PROJ).dvi
	ps2pdf $(PROJ).ps

clean:
	rm -f $(PROJ).aux \
	      $(PROJ).dvi \
	      $(PROJ).log \
	      $(PROJ).ps \
	      $(PROJ).out \
	      $(PROJ).toc \
	      $(PROJ).lof \
	      $(PROJ).lot

clean-all: clean
	rm -f $(PROJ).pdf
