LATEXSOURCE=Report.tex

Report.pdf: Report.tex ${LATEXSOURCE} 
		latexmk -pdf -pdflatex="pdflatex" -use-make $< 

clean:
		latexmk -CA
