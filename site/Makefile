.PHONY: build preview clean

build: clean
	quarto render && \
	mkdir -p ../_docs/workflows && \
	cp -r ../.github/workflows/* ../_docs/workflows

preview: clean
	quarto preview

clean:
	rm -rf _book
	$(MAKE) copy-files

copy-files:
	mkdir -p ../_docs/workflows && \
	cp -r ../.github/workflows/* ../_docs/workflows
