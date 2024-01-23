## Compiler Chain

	pdflatex --shell-escape main
	biber main
	glossaries main
	pdflatex --shell-escape main
	pdflatex --shell-escape main
