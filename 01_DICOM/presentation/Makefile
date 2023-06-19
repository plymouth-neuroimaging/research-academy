# SPDX-FileCopyrightText: 2023 Mark Thurston
#
# SPDX-License-Identifier: Apache-2.0

full:
	make quick bib quick

quick: presentation.tex
	xelatex presentation.tex

bib:
	biber presentation

clean:
	- rm -f *.out *.log *.aux *.pdf *.nav *.snm *.toc

bibclean:
	- rm -f *.bbl *.blg *.bcf *.run.xml
