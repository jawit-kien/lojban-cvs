all: drbible.html drbible.info

drbible.html: *.texinfo
	texi2html drbible.texinfo

drbible.info: *.texinfo
	makeinfo drbible.texinfo

clean:
	rm -f drbible.info drbible.html drbible_toc.html
