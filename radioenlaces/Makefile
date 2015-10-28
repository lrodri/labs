todo: guia.pdf guia2.pdf guia3.pdf

guia.pdf: guia.tex
	latexmk -pdf guia.tex

guia2.pdf: guia2.tex
	latexmk -pdf guia2.tex

guia3.pdf: guia3.tex
	latexmk -pdf guia3.tex
	
clean:
	latexmk -C guia guia2
