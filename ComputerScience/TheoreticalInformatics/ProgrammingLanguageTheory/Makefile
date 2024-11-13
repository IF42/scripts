TEX=pdfcsplain
SRC=src
TARGET=ProgrammingLanguagesTheory
OUTPUT=pdf


all: env
		$(TEX) --output-directory=$(OUTPUT) $(SRC)/$(TARGET).tex


clean:
		rm -rvf $(OUTPUT)


env:
		mkdir -pv $(OUTPUT)
