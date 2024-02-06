serve:
	mkdocs serve

build:
	mkdocs build

dev:
	docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material

help:
	@echo "serve - Start the live-reloading docs server."
	@echo "build - Build the documentation site."
	@echo "dev - Start the live-reloading docs server using Docker."
	@echo "help - Show this message."

.PHONY: serve build dev help