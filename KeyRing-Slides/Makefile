all: clean create

create:
# 	pdflatex -shell-escape Figures2.tex
# 	xelatex -shell-escape main.tex
# 	xelatex -shell-escape main.tex
	xelatex -shell-escape main-MSH.tex
	xelatex -shell-escape main-MSH.tex


clean:
	rm -rf *.aux  *.nav  *.vrb  *.log  *.out *.snm *.toc *.gz *.mtc* *.maf *.fls *.tmp *.bbl *.blg  *.mtc  *.bcf *.xml *.fdb_latexmk *.dep *.dpth *.log *.md5 *.auxlock img/*.dpth img/*.log img/*.md5

keyring:
	xelatex -shell-escape main-KeyRing.tex
	xelatex -shell-escape main-KeyRing.tex
