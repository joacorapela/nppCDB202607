all: rapelaVisionStmt.pdf rapelaCV.pdf rapelaPersonSpecification.pdf

rapelaVisionStmt.pdf: rapelaVisionStmt.tex
	pdflatex rapelaVisionStmt.tex
	bibtex rapelaVisionStmt.aux
	pdflatex rapelaVisionStmt.tex
	pdflatex rapelaVisionStmt.tex

rapelaPersonSpecification.pdf: rapelaPersonSpecification.tex
	pdflatex rapelaPersonSpecification.tex
	bibtex rapelaPersonSpecification.aux
	pdflatex rapelaPersonSpecification.tex
	pdflatex rapelaPersonSpecification.tex

%.pdf: %.tex
	pdflatex $<

