PANDOC = pandoc
PANDOCFLAGS = --self-contained -t html5 -c $(HOME)/.pandoc/github.css

all: lowWAFOMSobol-ja.html

%.html:%.md
	$(PANDOC) $(PANDOCFLAGS) -o $@ $<

#%.html:%.Rd
#	$(PANDOC) $(PANDOCFLAGS) -o $@ $<

lowWAFOMSobol-ja.html:lowWAFOMSobol-ja.Rmd
	Rscript -e "rmarkdown::render('lowWAFOMSobol-ja.Rmd')"
