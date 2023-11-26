PROJECT=TechnoparkMedkit
TEX=pdflatex
BUILDTEX=$(TEX) $(PROJECT).tex
LATEX_CMD=pdflatex
TARGET=Technopark

all: $(TARGET).pdf

pdf: $(TARGET).pdf

$(TARGET).pdf: clean
	$(BUILDTEX)
	@echo "Чтобы нормально скомпилировалось надо еще раз выполнить эти действия"
	$(BUILDTEX)
	@echo "Чтобы нормально скомпилировалось надо еще раз выполнить эти действия"
	$(BUILDTEX)
	rm -f ./*.ps ./*.dvi ./*.aux *.toc *.idx *.ind *.ilg *.log *.out *.brf *.blg *.bbl ./*.run.xml ./*.bcf ./chapters/*.aux ./chapters/*.log

clean:
	rm -f *.ps *.dvi *.aux ./chapters/*.aux *.toc *.idx *.ind *.ilg *.log *.out *.brf *.blg *.bbl ./*.run.xml ./*.bcf $(PROJECT).pdf ./chapters/*.log
