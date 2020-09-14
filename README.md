# Actionstest

This repository contians sample Angular 10 application with a source map generation actions workflow file actions.yml

On each commit on the branch master, the workflow generates build for the angular application, on successful generation of build files, workflow creates build status file containing name & size details of each file generated along with time taken to generate build. Along with that, it creates source map of the build files in the format of json, html & tsv with commit SHA as a name of the files.

At last,  workflow sends an email of the generated source map files to the configured email addresses of developers, collaborators etc. 
