build:  ## Create the static web site in dist/
	@hugo > /dev/null
clean:  ## remove all files from the distribution folder
	@rm -rf dist/ > /dev/null
post:   ## Add a new blog post
	@hugo new posts/${POST_NAME}.md > /dev/null
	@echo ${POST_TITLE} >> content/posts/${POST_NAME}.md
	@sed -i "" "s/${POST_NAME}/${POST_TITLE}/gi" "./content/posts/${POST_NAME}.md"
help:
	@echo "build: Create the static web site in dist/"
	@echo "clean: remove all files from dist/"
	@echo "POST_NAME=<file_name> POST_TITLE=<file_title> post: Add a new blog post"
	@echo "help: Display makefile help"