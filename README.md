# Hello World!!
My name is ZediWards

###
This branch "source" will be where my source code for my website will reside. The master branch will house my output directory that is needed to serve the static html files that is needed for the website.

####
I will include a .gitignore file within the Pelican file tree that will exclude the output directory from the source branch.

#####
Theoretical workflow for now:
- I will write articles locally within the content directory.
- To publish: I will update the output directory via pelican commands (pelican content -s publishconf.py)
  - Then push source code to source branch & output directory to master branch.
