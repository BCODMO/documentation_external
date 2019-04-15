# What is this?
The purpose of this folder is to contain all the documentation that can be read and used by the end user. 
The versioning is done by GIT, GitHub hosts the files. The files need to be written in reStructured Text. 
The documentation structure is build by Sphinx and ReadTheDocs have a webhook that update their page that hosts these pages. 

# File structure and naming
All files containing information seen by the end user start with DOC_*.rst. 
Other files that are necessray for Sphinx:

documentation_external (repo)  

> |-Readme.md  
> |-docs  
>
> > |- **index.rst** : toctree (table of contents), index file fort the documentation  
> > |- conf.py : Customization of Sphinx  
> > |- *Makefile* : Interface local development, do not touch  
> > |- *make.bat* : Interface local development, do not touch  
> > |- _build : output files go in here  
> > |- _static : include statice files like images  
> > |- _templates : Override Sphinx templates to customise look and feel  
> > |- **support.rst**  : Own documentation  
> > |- **DOC_*.rst**  : Own documentation  
