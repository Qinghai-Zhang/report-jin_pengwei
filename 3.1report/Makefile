default: report.pdf 

%.pdf : %.tex
	xelatex $<
	xelatex $<
clean:
	$(RM) *.aux *.bbl *.blg *.log *.dvi *.toc *~ *.xdv *.fls *.xml *.bcf *.out *.tmp *latexmk tikz/*.log sec/*.log

realclean:
	$(MAKE) clean
	$(RM) tikz/*.pdf *.pdf */*~ *~ 
