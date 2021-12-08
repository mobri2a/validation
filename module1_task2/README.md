# Module1_Task2
## Prerequisites
- Install hugo
- Install make
- Install sed
## Lifecycle
1) Clean the dist folder: ```make clean```
2) Add a blog post: ```make POST_NAME=\<file_name\> POST_TITLE=\<file_title\> post```
3) Publish the site: ```make build```