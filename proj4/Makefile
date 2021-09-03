# Projekt: proj4
# Autor:   Vojtìch Jurka
# 
#
proj4: proj4.tex
	latex proj4.tex
	bibtex proj4
	latex proj4.tex
	latex proj4.tex
	dvips proj4.dvi
	ps2pdf proj4.ps

clean: 
	rm proj4.ps proj4.pdf proj4.out proj4.log proj4.dvi proj4.aux proj4.blg proj4.bbl
