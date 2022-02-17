# Introduction 
This is a repo for updating firebase remote config. This code created according to Firebase Docs and spesifically edited to manage localization data.

# Getting Started
you need to follow these steps to start:
1.  install Node.js
2.	Add firebase admin keys under "/credentials" folder
3.	Manage firebase project key info in "index.js"
4.	Manage language support in "index.js" and update localization files under "localizable"
5.	(optional) Create a pipeline using azure-pipelines.yml
6.  run command "node index.js [get|publish|update] [test|staging|prod]"

