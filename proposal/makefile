MD  = $(wildcard *.md)
PDF = $(MD:.md=.pdf)

all: $(PDF)

%.pdf: %.md
	pandoc $< -o $@

cleanall:
	rm -f $(PDF)

.PHONY: all cleanall
