TEXFILE=proj5

all:
	latex $(TEXFILE).tex
	latex $(TEXFILE).tex
	dvips $(TEXFILE).dvi
	ps2pdf $(TEXFILE).ps
clean:
	rm -f $(TEXFILE).{aux,dvi,log,ps,nav,snm,toc,out}
