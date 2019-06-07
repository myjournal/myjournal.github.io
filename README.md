# My Journal

## Travis CI
Build URL: https://travis-ci.org/myjournal/myjournal.github.io

[![Build Status](https://travis-ci.org/myjournal/myjournal.github.io.svg?branch=source)](https://travis-ci.org/myjournal/myjournal.github.io)

## Steps to adding a new page

 - Create a new markdown file under docs/{category}
 - Naming convention: ```yyyy-mm-dd-page-title.md```
 
## Preview the changes

  - Preview changes with ```mkdocs serve```
  
## Deploy changes
  - Deploy changes with ```mkdocs gh-deploy --clean```
 
## Git repository details
  - Markdown files go in ```source``` branch
  - The ```mkdocs gh-deploy``` will push to the ```master``` branch which will be served live

