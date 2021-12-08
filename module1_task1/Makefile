build:
	@hugo > /dev/null
clean:
	@rm -rf dist/ > /dev/null
post:
	@hugo new posts/${POST_NAME}.md > /dev/null
	@echo ${POST_TITLE} >> content/posts/${POST_NAME}.md
	@sed -i "s/${POST_NAME}/${POST_TITLE}/gi" "./content/posts/${POST_NAME}.md"