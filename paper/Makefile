character-voice.pdf: character-voice.md
	pandoc --template=homework-template.tex \
		--latex-engine=xelatex \
		--filter pandoc-citeproc \
		--bibliography /home/jon/Dropbox/Papers/library.bib \
		-o $@ $<
	evince $@
