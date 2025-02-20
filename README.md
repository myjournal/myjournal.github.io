# My Journal
![Build Status](https://github.com/myjournal/myjournal.github.io/actions/workflows/deploy.yml/badge.svg)

## Steps to adding a new page

 - Create a new markdown file under docs/{category}
 - Naming convention: ```yyyy-mm-dd-page-title.md```
 
## Preview the changes

  - Preview changes with ```mkdocs serve```
  
## Deploy changes
  - Deploy changes with ```mkdocs gh-deploy --clean```
 
## Git repository details
  - Markdown files go in ```source``` branch
  - The ```mkdocs gh-deploy``` will push to the ```site``` branch which will be served live

