PAPERNAME=paper
TEXFILES =  *.tex *.bib *.sty

$(PAPERNAME).pdf : $(TEXFILES)
	pdflatex $(PAPERNAME)
	bibtex $(PAPERNAME)
	pdflatex $(PAPERNAME)
	pdflatex $(PAPERNAME)
clean:
	rm *.ps $(PAPERNAME).pdf *.dvi *.aux *.log *.blg *.bbl *~ *.ilg *.idx *.out *.in *.gz
