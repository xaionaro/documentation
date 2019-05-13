README.md:
	sh -c 'for f in [a-z]*.md; do echo -n "* $$f "| sed -e 's/.md//'g; cat $$f; done > README.md'

clean:
	rm -f README.md
