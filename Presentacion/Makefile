all: slides.pdf
dvi: slides.dvi
slides.pdf : slides.dvi
	dvipdf slides.dvi
slides.dvi: slides.tex
	latex slides.tex ; \
	latex slides.tex ;
clean : 
	rm -f *.aux *~ *.dvi *.nav *.out  *.snm *.toc *.pdf

