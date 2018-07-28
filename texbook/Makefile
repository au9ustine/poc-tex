.PHONY:

clean:
	rm -vf *.aux *.log *.out *.synctex.gz *.toc

clean-dist: clean
	rm -vf *.pdf

build: build21

build21:
	./shake.sh exercise21.tex
