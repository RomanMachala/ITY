TEXFILE=proj1

all:
	latex $(TEXFILE).tex
	dvips -t a4 $(TEXFILE).dvi
	ps2pdf -sPAPERSIZE=a4 $(TEXFILE).ps
clean:
	rm -f $(TEXFILE).{aux,dvi,log,ps}
