all:

install:
	install -d shinyapp ../bin/shinyapp
	install --mode 0444 -t ../bin/shinyapp shinyapp/*

clean:

distclean: clean
	rm -f ../bin/shinyapp

.PHONY: all install clean distclean
