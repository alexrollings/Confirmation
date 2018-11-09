LATEXSOURCE=ConfirmationReport.tex

ConfirmationReport.pdf: ConfirmationReport.tex ${LATEXSOURCE} 
		latexmk -pdf -pdflatex="pdflatex" -use-make $< 

clean:
		latexmk -CA
