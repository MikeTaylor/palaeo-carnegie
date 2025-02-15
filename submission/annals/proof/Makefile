proof-comments-formatted.md: proof-comments.md Makefile
	rm -rf $@
	cat $< | sed 's/^p\([0-9]*\)c\([0-9]*\)p\([0-9]*\)$$/**Page \1, column \2, paragraph \3.**<br \/>/' > $@
	chmod ugo-w $@

