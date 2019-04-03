# markdown-to-pdf-sample
This project is a sample of automating the process of converting markdown to a pdf with styles. The
yaml file is used for an Azure Pipelines build that runs whenever new changes are pushed to the master
branch. It uses the Markdown2Html task to convert the markdown to html and then uses html5-to-pdf to 
convert that html file into a pdf.

[![Build Status](https://dev.azure.com/boehmer/markdown-to-pdf-sample/_apis/build/status/scottboehmer.markdown-to-pdf-sample?branchName=master)](https://dev.azure.com/boehmer/markdown-to-pdf-sample/_build/latest?definitionId=35&branchName=master)
