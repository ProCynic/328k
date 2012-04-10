HW=21

all: hw$(HW).tex
	@echo "Making PDF"
	@pdflatex hw$(HW).tex && evince hw$(HW).pdf

clean: 
	@echo "Cleaning"
	@rm -rf *.log *.pdf *.idx *.aux *~